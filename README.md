# Validation Conclusion

## Learning Goals

- Use SQLAlchemy constraints and validators to validate data.
- Create forms using Flask-WTF and use WTForms validators.

***

## Key Vocab

- **HTML**: The HyperText Markup Language or HTML is the standard markup language for documents designed to be displayed in a web browser.
- **Validation**: Validation is an automatic check to ensure that data entered is sensible and feasible.
- **Form**: An HTML form is used to collect user input. The user input is most often sent to a server for processing.

***

## Conclusion

Data integrity is important because as developers we want to know what we are getting out of our programs and databases because
surprises can break our code. In the previous lessons we learned about database level validation using SQLAlchemy constraints and
we learned about Python level validation of data using the validator method. We can now create Flask-WTF forms and validate
the data users pass in to ensure we are passing the correct format of data to the backend and database. Combining these methods and techniques
can help us write code that is less prone to bugs and unexpected crashes.

***

## Resources

- [SQLAlchemy constraints](https://docs.sqlalchemy.org/en/14/core/constraints.html)
- [SQLAlchemy Validators](https://docs.sqlalchemy.org/en/14/orm/mapped_attributes.html)
- [Flask-WTF](https://flask-wtf.readthedocs.io/en/1.0.x/)
- [Jinja Templates](https://jinja.palletsprojects.com/en/3.1.x/templates/)
