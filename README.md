# US-Medical-Insurance
A short investigation into US medical insurance costs and the factors that can affect it

---

Using only the `csv` library and built-in Python modules, I look through the data in `insurance.csv`.
The data in question is in the form:
| Variable | Meaning |
| --- | --- |
| age | The patients' age in years |
| sex | The patients' sex |
| bmi | The paitients' [body mass index](https://en.wikipedia.org/wiki/Body_mass_index) |
| children | The total number of children the patient has |
| smoker | If the patient is a regular smoker |
| region | Which geographical quedrant the patient is located |
| charges | The patients' yearly medical insurance cost in USD$|

For example : 62, female, 26.29, 0, yes, southeast, 27808.7251

By using a `DictReader` object, I imported the data of each patient as a dictionary with the above variables as keys.  

From there, I created some functions to derive summary statistics from the data for each variable, further going on to explore some of the variables more specifically.  

Overall, this was a very short and simple project to grow acustomed to handling and exploring data in Python.

---

Data provided by [CodeCademy.com](https://www.codecademy.com/)
