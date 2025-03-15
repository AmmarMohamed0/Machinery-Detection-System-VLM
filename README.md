# MachineryVision 🚜🔍

## 📌 Introduction

MachineryVision is an AI-powered system designed to detect and analyze construction machinery in video feeds. Using OpenAI’s API and OpenCV, it identifies excavators and dump trucks, classifies their status (active/inactive), and provides structured analysis in real time. This project is ideal for construction site monitoring, equipment tracking, and automated documentation.

## ✨ Features

- 📷 **Real-time Machinery Detection**: Detects excavators and dump trucks in video feeds.
- 🎨 **Color Classification**: Identifies machinery colors.
- 🚦 **Activity Monitoring**: Determines if machinery is active or inactive.
- 🏢 **Company Recognition**: Extracts company logos or branding if available.
- 📝 **Structured Reporting**: Outputs results in a table format.
- 🔄 **Multithreading**: Efficient processing using concurrent threads.
- 🔧 **Configurable API**: Uses OpenRouter AI for flexible model selection.

## 🛠 Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.8+
- OpenCV
- NumPy
- OpenAI SDK
- dotenv

## 🚀 Usage

1. **Run the script**:
   ```sh
   python main.py
   ```
2. **Processing Video Feeds**:
   - The script captures frames from `f1.mp4`, applies AI analysis, and outputs structured results.
3. **Output Example**:
   ```
   | Machinery Name | Color  | Status    | Company Name | Area  |
   |---------------|--------|-----------|--------------|-------|
   | Excavator     | Yellow | Active    | CAT          | area  |
   | Dump Truck   | Red    | Inactive  | Komatsu      | area1 |
   ```

## 🏗 Technologies Used

- **Python** 🐍
- **OpenCV** 🎥
- **NumPy** 🔢
- **OpenAI API via OpenRouter** 🤖
- **dotenv** 🔑
- **Threading** ⚡
