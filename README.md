# Fyysikkospeksi
![Fyysikkospeksi logo](img/speksilogo.png)

[Website](https://fyysikkospeksi.fi/) of the *Physicist Spex* (Fyysikkospeksi).

<img src="https://i.imgur.com/iPDAw8R.png" alt="Screenshot" width="500"/>


## Development

1. Install [Node](https://nodejs.org/)
2. Clone the repository
3. Open terminal in repository and run
   ```shell
   npm install
   ```
4. To start development, run
   ```shell
   gulp watch
   ```
   
The `gulp` command runs browser-sync which updates the opened development html on updates to Sass (or HTML) files.


## Production
#### To update site on Otax:
1. `ssh` to Otax. Ask how to do this from Fyysikkokilta Tech Support or the [Communications Officer](https://www.fyysikkokilta.fi/raati/).
2. Go to the *fyysikkospeksi* folder. 
   ```shell
   cd ~/www/speksi
   ```
4. Update folder with newest changes.
   ```shell
   git pull
   ```
5. Fix permissions by running
   ```shell
   chmod -R 755 .
   ```
6. Enjoy, site should be online at [fyysikkospeksi.fi](https://fyysikkospeksi.fi/).
