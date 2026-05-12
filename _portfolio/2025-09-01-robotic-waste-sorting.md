---
title: "Intelligent Robotic Arm Waste Sorting System"
excerpt: "Multimodal Interactive Computer Vision System: Natural language-controlled trash sorting using CLIP, Qwen LLM, and Jetson Nano"
collection: portfolio
---

## 🤖 项目简介 | Project Overview

本项目集成了图像识别、自然语言处理、多模态交互与机械臂控制，设计并实现了一套智能垃圾分拣系统。用户通过文本或语音指令与系统交互，系统通过视觉感知、语义理解与运动规划，自动完成垃圾的识别、定位与分类抓取。[演示视频](https://www.bilibili.com/video/BV1z2BjBzEWi/?share_source=copy_web&vd_source=27c29d7ca7873e78adf463cbe659a1d9)

A comprehensive system integrating computer vision, natural language processing, and robotic control. Users interact with the system via natural language (text/voice) commands, enabling automated waste sorting through visual perception, semantic understanding, and precise robotic manipulation.

## 🏆 项目特色 | Key Features

### 1. **多模态交互** | Multimodal Interaction
- 支持文本指令和语音命令输入
- 基于Qwen-7B大语言模型的指令理解和任务规划
- 系统Prompt工程确保指令被正确解析

### 2. **计算机视觉** | Computer Vision
- **CLIP微调的分类模型**: 垃圾类别识别（可回收、有害、厨余等）
- **目标检测**: 工作区域内垃圾的位置定位
- **坐标变换**: 图像坐标到机械臂工作空间的映射

### 3. **机械臂控制** | Robotic Arm Control
- 从指令到执行的完整控制流程
- 运动规划与路径优化
- 实时反馈和碰撞检测
- 精确的抓取和放置操作

### 4. **边缘计算** | Edge Computing
- **Jetson Nano**: 作为核心控制器
- 本地模型推理，无需云服务
- 低延迟、高可靠性的系统响应

## 🛠️ 技术栈 | Tech Stack

- **计算机视觉**: CLIP微调、Object Detection
- **LLM集成**: Qwen-7B for instruction parsing and task planning
- **边缘计算**: Jetson Nano (NVIDIA Jetson ecosystem)
- **机械臂**: 通用机械臂API接口
- **传感器**: 摄像头、麦克风、压力传感器
- **编程语言**: Python, C++ (for robotic control)

## 📋 系统架构 | System Architecture

![系统架构与方法图]({{ site.baseurl }}/images/rubbish.png)
*机械臂垃圾分拣系统架构 | Robotic Waste Sorting System Architecture*

```
用户指令 (Text/Voice)
         ↓
    语言处理 (Qwen-7B)
         ↓
    任务规划 & 指令生成
         ↓
    视觉感知 (CLIP + Detection)
         ↓
    坐标变换 & 路径规划
         ↓
    机械臂控制 & 执行
         ↓
    实时反馈与监控
```

## 🎯 核心工作 | Main Contributions

**作为队长**:
- 系统架构设计与技术方案选型
- 多模态交互模块的集成与测试
- 视觉感知与机械臂控制的协调

**具体技术**:
- CLIP模型微调用于垃圾分类
- LLM Prompt设计实现复杂指令解析
- Jetson Nano端到端系统集成与优化

## 📊 性能指标 | Performance Metrics

- **分类准确率**: 92%+ on custom waste classification dataset
- **物体检测mAP**: 0.85+ for common trash items
- **端到端延迟**: <500ms (from instruction to robotic execution)
- **系统可用性**: 99.2% uptime in 24-hour continuous operation test
- **分拣成功率**: 94% for successful pick-and-place operations

## 🧪 测试与验证 | Testing & Validation

- 单元测试: 各模块独立功能验证
- 集成测试: 多模块协同工作验证
- 系统测试: 完整工作流程验证
- 用户验收测试: 实际使用场景评估

## 💡 创新点 | Innovations

1. **自然语言与机械臂的一体化** - First attempt in our lab to fully integrate NLP with robotic control
2. **端到端学习** - From language understanding to physical execution in a single pipeline
3. **实时自适应** - System adapts to different trash items and environmental conditions
4. **边缘计算方案** - Efficient deployment on resource-constrained Jetson Nano

## 🚀 实际应用 | Expected Real-World Applications

- Autonomous waste sorting facilities
- Smart recycling centers with multi-language support
- Educational robotics platform for AI & robotics integration
- Research platform for human-robot interaction studies

---

**Status**: Completed & Demonstrated | 已完成与展示  
**Timeline**: 2025.09 - 2026.01  
**Team Size**: 3 members (Led by Kexin Wang)  
**Key Achievement**: Full system integration and successful real-world deployment demonstration
