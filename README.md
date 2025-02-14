# form-task
## **Aim**  
To create a **personal details registration form** using **HTML** with basic form elements such as input fields, radio buttons, dropdowns, and a submit button.  

---

## **Procedure**  
1. **Create an HTML file (`index.html`)** to structure the form.  
2. Use the `<form>` element to define the input fields.  
3. Add a `<fieldset>` with a `<legend>` to group personal details.  
4. Implement the following fields inside a `<table>`:  
   - **Dropdown (`<select>`)** for Salutation.  
   - **Text inputs (`<input type="text">`)** for First Name and Last Name.  
   - **Radio buttons (`<input type="radio">`)** for Gender selection.  
   - **Textarea (`<textarea>`)** for Address input.  
   - **Submit button (`<input type="submit">`)** for form submission.  
5. Use the `<center>` tag to align elements (though it's outdated in modern HTML).  
6. Save and run the file in a browser to test the form.  

---

## **Program**  
```html
<!DOCTYPE html>
<html>

<head>
    <title>Registration Form</title>
</head>

<body>
    <center>
        <h2>Form Task</h2>
        <form>
            <fieldset style="width: 300px; margin: auto;">
                <legend>Personal details</legend>
                <table>
                    <tr>
                        <td>
                            <label>Salutation:</label>
                            <select>
                                <option>--None--</option>
                                <option>Mr.</option>
                                <option>Mrs.</option>
                            </select>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <label>First name: <input type="text" placeholder="Enter Your First Name"></label>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <label>Last Name: <input type="text" placeholder="Enter Your Last Name"></label>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <label>Gender:</label>
                            <input type="radio" name="gender"> Male
                            <input type="radio" name="gender"> Female
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <label>Address:</label>
                            <textarea name="Address"></textarea>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <input type="submit" value="Submit">
                        </td>
                    </tr>
                </table>
            </fieldset>
        </form>
    </center>
</body>

</html>
```

---

## **Output Screenshot**  
📸 *(Attach the screenshot of the form here in GitHub's README file.)*  

---

## **Expected Output**  
- A structured **form** that collects **personal details**.  
- Fields for **salutation, name, gender, address**, and a **submit button**.  
- Properly aligned form using a **fieldset** and **table layout**.  

---

## **Observations**  
✔ Form elements are correctly structured and aligned.  
✔ User input is collected through various form fields.  
✔ Submit button allows data submission.  

---

## **Conclusion**  
The **HTML Registration Form** was successfully created using form elements, improving my understanding of **basic HTML form structures**.  

---
