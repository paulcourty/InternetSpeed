# Internet Speed

<br>

An Internet Speed test in Python, to measure wifi quality - **download & upload speed**, **latency** - through time.

I wrote this script when going to l'Ile d'Yeu (a cool island in France, definitely recommend) to check the overall wifi quality. Now that remote work is common, it is really important to have a reliable wifi connection.

<br>



## Results

<br>

Wifi test in Yeu, France:

- **Download Speed** is particularly unreliable 
- **Latency** is too high to make smooth video calls

<br> 

![Wifi Yeu](https://github.com/paulcourty/InternetSpeed/blob/main/Graphs%20&%20Data/Wifi%20Yeu.png)

<br>

Wifi test in Bath, UK:

- All good !

<br>

![Wifi Bath](https://github.com/paulcourty/InternetSpeed/blob/main/Graphs%20&%20Data/Wifi%20Bath.png)

<br>



## How to run

<br>

You can run the `internet_speed.ipynb` script by simply cloning this repository (`git` or manually downloading the folder). Then, go into a terminal, navigate to the cloned repository, and install the necessary Python dependencies:

<br>

For **Unix/macOS**:

```sh
python3 -m venv .env_InternetSpeed
source .env_InternetSpeed/bin/activate
pip install -r requirements.txt
```

For **Windows**:

```sh
py -m venv .env_InternetSpeed
call .env_InternetSpeed/Scripts/activate
pip install -r requirements.txt
```

<br>

The Jupyter environment will take a bit of time to download. To run `internet_speed.ipynb`:

```sh
jupyter lab
``` 

<br>

When the Jupyter web interface opens, navigate to `internet_speed.ipynb` to open & run the Notebook !