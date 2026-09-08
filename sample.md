import pandas as pd

data = {
    "Name": ["John", "Jane", "Mark", "Anna"],
    "Age": [25, 30, 28, 22],
    "City": ["Manila", "Cebu", "Davao", "Quezon City"],
    "Sales": [15000, 22000, 18000, 12000]
}

df = pd.DataFrame(data)

print(df)