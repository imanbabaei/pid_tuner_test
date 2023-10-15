# Quick Start

In this section, we'll provide you with a quick introduction to using PID Tuner to tune your PID controllers. By the end of this guide, you'll be able to set up a basic tuning process and optimize your control system.

## Setting Up a Basic Tuning Process

1. **Import the PID Tuner package**: First, import the PID Tuner package in your Python script or Jupyter Notebook.

   Import the `pid_tuner` package.

2. **Create a Tuning Configuration**: Create a tuning configuration object. You can specify your FOPDT model or historical data for system identification, as well as other tuning parameters.

   Create a configuration object, e.g., `config = pid_tuner.TuningConfig()`.

3. **Initialize the Tuner**: Initialize the tuner with your configuration.

   Initialize the tuner, e.g., `tuner = pid_tuner.PIDTuner(config)`.

4. **Run the Tuning Process**: Run the tuning process, and PID Tuner will automatically optimize the PID controller parameters for your system.

   Run the tuning process, e.g., `tuner.tune()`.

5. **View and Analyze the Results**: After tuning, you can access the optimized PID parameters and view performance metrics.

   Access the optimized parameters and performance metrics, e.g., `tuned_params = tuner.get_tuned_parameters()` and `performance_metrics = tuner.get_performance_metrics()`.

6. **Customize and Iterate**: If necessary, you can further customize the tuning process and iterate to achieve the desired control performance.

## Additional Resources

- For more in-depth guidance and advanced features, refer to the relevant sections in this documentation.
- Explore the examples provided to see how PID Tuner can be applied to real-world control systems.

Now that you have successfully completed a basic tuning process with PID Tuner, you're ready to apply this knowledge to your specific control system. The following sections will provide more details on advanced features, system identification, and using the graphical user interface (GUI) for tuning.

Next, we'll dive into tuning your PID controller using a user-defined FOPDT model. Please proceed to the "FOPDT Model Tuning" section for detailed instructions.
