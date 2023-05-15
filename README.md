# understanding_cs_convert_binary_into_decimal_and_vice_versa

# Convert a binary number to decimal
Converting between binary and decimal numbers is relatively straightforward. To convert a binary number to decimal, we add up the magnitudes with a 1 in them. For example, 1011 in binary would be converted to 8 + 0 + 2 + 1 = 11 in decimal. (2³ + 2¹ + 2⁰)

# Converting from decimal to binary
Converting from decimal to binary requires subtracting **the largest number that fits without exceeding the decimal value.** For example, to convert 55 to binary, **we subtract the largest power of 2**, which is 32, from the decimal number. Then, we repeat this process until the number reaches zero. Any remaining positions without a 1 are filled with 0s. Thus, 55 in decimal becomes 110111 in binary.
