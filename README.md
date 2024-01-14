# qb-clothing-np-outfit-input

https://discord.gg/FT9s9rvtXS

![IMG](https://cdn.discordapp.com/attachments/1155541970597449838/1196202278554701945/image.png?ex=65b6c52f&is=65a4502f&hm=0d699b029134df43e2242f4a46eadb0d6eb2e309fc65442066891f63e9d2858a&)


- Replace your style.css with the one below

  - CSS BELOW

```css
.clothing-menu-save-outfit-name {
    display: none;
    position: relative;
    width: 35vh;
    height: 20vh;
    background: #001321;
    margin: 0 auto;
    top: 40%;
    border-radius: 2px;
}

.clothing-menu-save-outfit-name-buttons {
    position: absolute;
    bottom: 0;
    width: 100%;
    height: 17%;
    margin: 0 auto;
    left: 0;
    right: 0;
}

.clothing-menu-save-outfit-name-button {
    position: relative;
    background: radial-gradient(50% 50% at 50% 50%, rgba(0, 249, 185, 0.10) 0%, rgba(0, 249, 185, 0.15) 100%);
    width: 50%;
    height: 100%;
    float: left;
    text-align: center;
    line-height: 3vh;
    transition: all 1s linear;
    cursor: pointer;
}

.clothing-menu-save-outfit-name-button2 {
    position: relative;
    background: radial-gradient(50% 50% at 50% 50%, rgba(249, 0, 0, 0.10) 0%, rgba(249, 0, 0, 0.15) 100%);
    width: 50%;
    height: 100%;
    float: left;
    text-align: center;
    line-height: 3vh;
    transition: all 1s linear;
    cursor: pointer;
}

.clothing-menu-save-outfit-name-button>p {
    text-transform: uppercase;
    color: #00F9B9;
    font-family: 'Poppins', sans-serif;
    font-size: 10px;
    font-style: normal;
    font-weight: 800;
    letter-spacing: 0.5px;
}

.clothing-menu-save-outfit-name-button2>p {
    text-transform: uppercase;
    color: #CF5F76;
    font-family: 'Poppins', sans-serif;
    font-size: 10px;
    font-style: normal;
    font-weight: 800;
    letter-spacing: 0.5px;
}

.clothing-menu-save-outfit-name-header {
    position: relative;
    width: 100%;
    height: 20%;
    text-align: center;
    line-height: 4.5vh;
}

.clothing-menu-save-outfit-name-header>p {
    color: #00F9B9;
    text-shadow: 0px 0px 50px #00F9B9;
    font-family: 'Poppins', sans-serif;
    font-size: 24px;
    font-style: normal;
    font-weight: 800;
    letter-spacing: 1.2px;
}

#outfit-name {
    position: absolute;
    margin: 0 auto;
    left: 0;
    right: 0;
    bottom: 40%;
    background: none;
    border: none;
    outline: none;
    width: 90%;
    height: 20%;
    text-align: center;
    background: radial-gradient(50% 50% at 50% 50%, rgba(255, 255, 255, 0.05) 0%, rgba(255, 255, 255, 0.10) 100%);
    transition: all 1s linear;
}

#outfit-name {
    color: #ededed;
    font-family: 'Poppins', sans-serif;
    font-size: 1.75vh;
    letter-spacing: 0.1vh;
    text-transform: uppercase;
    font-weight: bold;
}

#outfit-name::placeholder {
    color: rgba(255, 255, 255, 0.50);
    font-family: 'Poppins', sans-serif;
    font-size: 1vh;
    font-style: normal;
    font-weight: 800;
    letter-spacing: 0.75px;
}
```

- HTML

```html
        <div class="clothing-menu-save-outfit-name">
            <div class="clothing-menu-save-outfit-name-header">
                <p id="outfit_name" data-tkey="outfit_name">Outfit Name</p>
            </div>

            <input type="text" id="outfit-name" placeholder="Outfit Name">

            <div class="clothing-menu-save-outfit-name-buttons">
                <div class="clothing-menu-save-outfit-name-button" id="save-outfit-save">
                    <p data-tkey="btn_confirm">Confirm</p>
                </div>
                <div class="clothing-menu-save-outfit-name-button2" id="cancel-outfit-save">
                    <p data-tkey="btn_cancel">Cancel</p>
                </div>
            </div>
        </div>
```
