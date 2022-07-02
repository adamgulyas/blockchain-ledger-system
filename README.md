# Blockchain Ledger System

A blockchain-based ledger system, complete with a user-friendly web interface. This ledger allows partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

## Usage

### Environment

Requires Python >= 3.7.

Activate your Python virtual environment. For example, with Anaconda:
```sh
conda activate <env>
```

### Dependencies

These installations are required to build the application. Newer package versions may be used, but be aware that library updates may introduce errors.

```sh
pip install pandas==1.4.3
pip install streamlit==1.10
```

### Run

In a terminal shell within the project directory, serve the application with `streamlit run pychain.py`

## Application

![A screenshot of the PyChain Streamlit app](/images/st-app.png)