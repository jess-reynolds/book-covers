1. Copy this folder
2. Open terminal
3. cd to this folder
4. Run "npm install"
5. Run "npm run start"
6. Go to localhost:8080 to see the site



title {
  font-family: "Merriweather", serif;
  text-transform: lowercase;
  color: black;
  font-size: 13rem;
  text-align: center;
  letter-spacing: 0.06em;
  margin-top: -1rem;
  margin-bottom: -2rem;
}

.sub-title {
  color: $wred;
  font-family: "Roboto Condensed", sans-serif;
  text-align: center;
  font-size: 2rem;
  text-transform: uppercase;
  letter-spacing: 0.1em;
}

.shoe-container {
  position: relative;

  img {
    width: 100%;
    padding: 0 2rem;
  }
}

.sticker__wrap {
  position: absolute;
  bottom: 2rem;
  right: 2rem;

  border-radius: 10rem;
  border: 0.1rem solid $wred;
}

.sticker {
  color: white;
  background-color: $wred;
  font-family: "Roboto Condensed", sans-serif;
  display: flex;

  width: 10rem;
  height: 10rem;

  align-items: center;
  justify-content: center;

  text-transform: uppercase;
  font-size: 1.5rem;
  text-align: center;

  border-radius: 5rem;
  border: 0.1rem solid white;
}

.name {
  font-family: "Merriweather", serif;
  font-size: 3.3rem;
  text-transform: capitalize;
  text-align: center;
  letter-spacing: 0.08em;
  padding-bottom: 1rem;.