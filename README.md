# github-final-project
def calculate_simple_interest(p, t, r):
    interest = p * t * r
    return interest

# Taking inputs from the user
p = float(input("Enter the principal amount: "))
t = float(input("Enter the time period in years: "))
r = float(input("Enter the annual rate of interest (as a decimal, e.g., 0.05 for 5%): "))

# Calculating simple interest
si = calculate_simple_interest(p, t, r)

print(f"Simple Interest: {si}")

