# Automatic-lightening-controller
# Automatic Lighting Controller

print("AUTOMATIC LIGHTING CONTROLLER")
print("-----------------------------")

while True:

    light_level = float(input("\nEnter light level (0-100): "))

    if light_level < 30:
        print("Light level: LOW")
        print("Lights: ON")

    elif light_level >= 70:
        print("Light level: HIGH")
        print("Lights: OFF")

    else:
        print("Light level: NORMAL")
        print("Lights: OFF")

    choice = input("\nCheck again? (yes/no): ")

    if choice.lower() != "yes":
        print("\nLighting controller stopped.")
        break
