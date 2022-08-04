# HT Condor

High Throughput Compuing (HTC)

– Running multiple independent
instances of software on multiple
processors at the same time

– Long time periods

– Generally runs on clusters of
commodity hardware


## Getting started: How to submit jobs

› Choosing a “Universe” for your job: Standard, Grid, Vanilla

› Make your job “batch-ready” : non-interactive with organised data

› Creating a submit description file: A plain ASCII text file -> condor_example

› Run condor_submit on your submit description file


## Usage

```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Inspiration:
[Website 1](https://services.ncl.ac.uk/media/sites/servicesites/itserviceold/communicationcollaborationandresearch/condor/Worked_Condor_Example_Simple_C_Add.pdf)
[Website 2](https://www.cs.cmu.edu/~jonas/doc/CondorTutorial_SInRG_Workshop.pdf)
