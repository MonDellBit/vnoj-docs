# Judge Configuration

To run the judge, simply do `python main.py <bridge hostname> -p <bridge port>`.
But before you run the judge, you must configure it.

## `judge.json`

`judge.json` is the only configuration file for the DMOJ judge. It specifies directories to search for
problems, and also defines the execution environment.

### Authentication

All judges are authenticated to the bridge in order to avoid rogue judges returning false data.