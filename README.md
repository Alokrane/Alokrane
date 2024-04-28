import random

# Define the colors used in the 91 Club game
colors = ['red', 'blue', 'green']

# Function to predict color
def predict_color():
    # Randomly select a color from the list
    predicted_color = random.choice(colors)
    return predicted_color

# Main function
def main():
    print("Welcome to the 91 Club Color Prediction Bot!")
    while True:
        input("Press Enter to predict a color...")
        predicted_color = predict_color()
        print("Predicted color:", predicted_color)

if __name__ == "__main__":
    main()
