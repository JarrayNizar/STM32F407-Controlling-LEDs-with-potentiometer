# STM32F407-Controlling-LEDs-with-potentiometer
# Configuration Steps in CubeIDE
Configure GPIOs for the LEDs (PD12, PD13, PD14, PD15):

Open the .ioc file in CubeIDE.
Set pins PD12, PD13, PD14, and PD15 as GPIO_Output.

# Configure the ADC to read the potentiometer value:
Set pin PA1 as ADC1_IN1.
Enable ADC1 with a 12-bit resolution.

# Generate the initial code:
Click on "Project > Generate Code" to generate the configuration files.

# MX_ADC1_Init: Configures ADC1 to read the analog value from PA1.
# MX_GPIO_Init: Initializes the GPIOs for the LEDs on PD12 to PD15.
# Main loop: The potentiometer value is continuously read, and the LEDs are turned on or off based on this value.
