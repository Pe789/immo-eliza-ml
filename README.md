# immo-eliza-ml


## 🏢 Description

In this project, Machine Learning is used to predict prices of Belgian Houses.  The available data was scraped from immoweb.be, cleaned and analyzed in a previous project.  Only some preprocessing was altered for the categorical data.

## 📦 Repo structure (still to replace)

```
.
├── src/
│   ├── openspace.py
│   ├── table.py
│   └── utils.py
├── .gitignore
├── main.py
├── new_colleagues.csv
├── output.csv
└── README.md
```

## 🛎️ Usage (still to replace)

1. Clone the repository to your local machine.

2 .To run the script, you can execute the `main.py` file from your command line:

    ```
    python main.py
    ```

3. The script reads your input file, and organizes your colleagues to random seat assignments. The resulting seating plan is displayed in your console and also saved to an "output.csv" file in your root directory. 

```python
input_filepath = "new_colleagues.csv"
output_filename = "output.csv"

# Creates a list that contains all the colleagues names
names = utils.read_names_from_csv(input_filepath)

# create an OpenSpace()
open_space = OpenSpace()

# assign a colleague randomly to a table
open_space.organize(names)

# save the seat assigments to a new file
open_space.store(output_filename)

# display assignments in the terminal
open_space.display()
```
## ⏱️ Timeline

This project took 1 week for completion.

## 📌 Personal Situation
This project was done as part of the AI Boocamp at BeCode.org. 


