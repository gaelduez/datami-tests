# datami-tests

Testing Datami widget to edit and validate CSV files [https://datami.multi.coop/](https://datami.multi.coop/).

## purpose

Demonstrate and document how we can use Datami and other components to:

- ease the edition of a csv file stored in Github 
- constraint the display of fields in the Datami widget
- investigate how we can use github actions to ensure that the csv file structure and or content is valid according to a model.

The approach of Datami component is 

1. to rely on Github to store the CSV file
2. offer a html widget to visualize or edit content of the file for users who may not want to use Github directly
3. automate the push of modifications to the data done via the widget as Github pull requests

![datami component](datami-components.excalidraw.png)


## content

- examples/csv/data: data files and related resources files to validate in CI
- examples/csv/model: model for the csv data
- .github/workflows: actions to automate validation
- example/csv/widget: widget and widget configuration examples

## References

- [https://datami.multi.coop/](https://datami.multi.coop/)
- [Datami parameter doc](https://datami-docs.multi.coop/docs-gitfile?locale=en#keys-for-the-options-parameter-for-csv-and-tsv-files)
- [Table Schema | Data Package (v1)](https://specs.frictionlessdata.io//table-schema/)
- [frictionless-ci | Frictionless Repository](https://repository.frictionlessdata.io/)