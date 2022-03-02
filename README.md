# Publisher-subscriber message service
Reliable publish-subscribe service with Python and ZeroMQ

**Group members**:
1. [Alexandre Abreu](https://github.com/a3brx)
2. [Diana Freitas](https://github.com/dianaamfr)
3. [Juliane Marubayashi](https://github.com/Jumaruba)
4. [Simão Lúcio](https://github.com/yolonhese)

## How to run the program

### Constraints

This project must be executed in unix environment, since the `zqm` does not support windows.

### Virtual environment

Make sure you have `python 3` and `pipenv` installed as a global dependecy.

To install the dependencies (from `src/`):

```bash
source pipenv install
```

To activate the python environment that is used in the project run the following command (from `src/`):

```bash
source pipenv shell
```
### How to execute

To run the project the only necessary command is:

```bash
python -m service [server | subscriber <messages_filename> <id>| publisher <topics_filename> <id>]
```
