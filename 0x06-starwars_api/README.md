**Star Wars Characters**

This project is a script that retrieves and prints all characters of a Star Wars movie based on the provided Movie ID.

### Prerequisites
- Python 3.x
- `requests` module

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/alx-interview.git
   ```

2. Navigate to the directory:
   ```bash
   cd alx-interview/0x06-starwars_api
   ```

3. Install the `requests` module:
   ```bash
   pip install requests
   ```

### Usage
Run the script `0-starwars_characters.py` with the Movie ID as the first positional argument:
```bash
./0-starwars_characters.py 3
```
Replace `3` with the desired Movie ID. For example, `3` corresponds to "Return of the Jedi".

### Example Output
```plaintext
Luke Skywalker
C-3PO
R2-D2
Darth Vader
Leia Organa
Obi-Wan Kenobi
Chewbacca
Han Solo
Jabba Desilijic Tiure
Wedge Antilles
Yoda
Palpatine
Boba Fett
Lando Calrissian
Ackbar
Mon Mothma
Arvel Crynyd
Wicket Systri Warrick
Nien Nunb
Bib Fortuna
```

### Notes
- This script utilizes the Star Wars API to fetch character data.
- Each character's name is displayed on a separate line, following the same order as the characters list in the `/films/` endpoint.

### Repository Information
- GitHub Repository: [alx-interview](https://github.com/alx-interview)
- Directory: `0x06-starwars_api`
- File: `0-starwars_characters.py`
