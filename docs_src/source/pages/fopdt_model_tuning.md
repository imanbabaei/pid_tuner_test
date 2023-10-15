# FOPDT Model Tuning

In this section, you will learn how to use PID Tuner to optimize your PID controller based on a user-defined First-Order Plus Dead Time (FOPDT) model. This method is particularly useful when you have prior knowledge of your system's dynamics.

## Steps for FOPDT Model Tuning

1. **Import the PID Tuner package**: Start by importing the PID Tuner package in your Python script or Jupyter Notebook.

2. **Define the FOPDT Model**: Define your system's FOPDT model by specifying the parameters: Process Gain (Kp), Time Constant (Tau), and Dead Time (Td).

3. **Create a Tuning Configuration**: Create a tuning configuration object and set the FOPDT model you've defined.

4. **Initialize the Tuner**: Initialize the tuner with your configuration.

5. **Run the Tuning Process**: Run the tuning process, and PID Tuner will automatically optimize the PID controller parameters based on your FOPDT model.

6. **View and Analyze the Results**: After tuning, you can access the optimized PID parameters and performance metrics.

7. **Customize and Iterate**: If necessary, you can further customize the tuning process and iterate to achieve the desired control performance.

## Example: FOPDT Model Tuning

Here's a quick example of how to perform FOPDT model tuning using PID Tuner:

1. Import the PID Tuner package.

2. Define your FOPDT model:

   - Process Gain (Kp) = 2.0
   - Time Constant (Tau) = 1.5
   - Dead Time (Td) = 0.5

3. Create a tuning configuration:

```python
   config = pid_tuner.TuningConfig()
   config.set_fopdt_model(Kp=2.0, Tau=1.5, Td=0.5)
```