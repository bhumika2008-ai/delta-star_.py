print("DELTA (Δ) TO STAR (Y) CONVERSION")

# Input Delta resistances
RAB = float(input("Enter RAB (Ohm): "))
RBC = float(input("Enter RBC (Ohm): "))
RCA = float(input("Enter RCA (Ohm): "))

# Sum of Delta resistances
S = RAB + RBC + RCA

# Star resistances
RA = (RAB * RCA) / S
RB = (RAB * RBC) / S
RC = (RBC * RCA) / S

# Display results
print("\n--- STAR RESISTANCES ---")
print("RA =", round(RA, 2), "Ohm")
print("RB =", round(RB, 2), "Ohm")
print("RC =", round(RC, 2), "Ohm")# delta-star_.py
A python program for delta to start conversion
