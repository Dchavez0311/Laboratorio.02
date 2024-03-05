# Laboratorio.02
from apps import apps
apps.run(debug=True)
# List of characters to remove
chars_to_remove = [...]
# List of column names to clean
cols_to_clean = [...]

# Loop for each column in cols_to_clean
for col in cols_to_clean:
    # Loop for each char in chars_to_remove
    for char in chars_to_remove:
        # Replace the character with an empty string
        apps[col] = apps[...].apply(lambda x: x.replace(..., ...))
        
# Print a summary of the apps dataframe
print(...)
