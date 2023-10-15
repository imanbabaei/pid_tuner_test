# Overview

PID Tuner is a Python package designed to streamline the process of tuning PID (Proportional-Integral-Derivative) controllers for various control systems. Whether you have a known First-Order Plus Dead Time (FOPDT) model or you need to identify one from historical system data, PID Tuner simplifies the tuning process, enabling you to achieve optimal control performance with ease.

## Key Features

1. **FOPDT Model Tuning:** PID Tuner allows you to tune your PID controller based on a user-defined FOPDT model. This model provides crucial insights into your system's dynamics, making it easier to optimize control parameters.

2. **System Identification:** If you lack a predefined FOPDT model, PID Tuner can help identify the model from historical data. This feature is invaluable for systems with complex and uncertain dynamics.

3. **Graphical User Interface (GUI):** The package provides a user-friendly GUI built using ipyvuetify, simplifying the entire tuning process. You can easily visualize control performance and adjust parameters in real-time.

4. **Integration with Gekko and Scipy:** PID Tuner leverages powerful optimization libraries like Gekko and Scipy to fine-tune PID controller parameters efficiently.

5. **Customizable Reporting:** The package generates comprehensive reports, including control parameter values, control performance metrics, and tuning history, helping you document your progress and results.

## Getting Started

Before you dive into using PID Tuner, make sure you have it installed. You can install it using pip:

```bash
pip install pid-tuner
```

Once you've installed the package, check out the tutorials and examples provided in this documentation to learn how to use PID Tuner effectively.

Table of Contents
Overview (You're here)
Installation
Quick Start
FOPDT Model Tuning
System Identification
GUI Usage
Advanced Features
Troubleshooting
Examples
API Reference
Release Notes
Acknowledgments
License