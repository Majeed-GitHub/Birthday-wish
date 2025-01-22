# Happy Birthday Card

A Customizable Web based birthday card to wish your friends and family in a unique way.

Check out the Previews -

- [Without Scroll Message](https://happy-birthday-card.vercel.app/)
- [With Scroll Message](https://hbd-card.netlify.app/)

If you liked it, please consider giving it star a 🤩⭐.

---

## How to setup

Here are the methods to set it up for yourself.

### Remote Deployment

- Vercel Deploy

  [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FAnshumanMahato%2FHappy-Birthday-Card&env=NAME,PIC&envDescription=NAME%20-%3E%20Name%20of%20the%20Receiver%20%7C%20PIC%20-%3E%20web%20url%20of%20a%20picture%20of%20the%20receiver&envLink=https%3A%2F%2Fgithub.com%2FAnshumanMahato%2FHappy-Birthday-Card%2Fblob%2Fmain%2Fdocs%2Fvariables.md&project-name=happy-birthday-card&repo-name=happy-birthday-card&demo-title=Happy%20Birthday%20Card&demo-description=This%20is%20a%20web%20based%20interactive%20birthday%20card.&demo-url=https%3A%2F%2Fhappy-birthday-card.vercel.app%2F&demo-image=https%3A%2F%2Ftelegra.ph%2Ffile%2Fac886529ccc3843552f81.png)

- Netlify Deploy

  [![Deploy with NEtlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Majeed-GitHub/Birthday-wish)

Remote deployment will require you to specify some mandatory Evironment Variables,

- NAME: Name of the receiver.

- PIC: Url of the pic to be loaded in the card. If don't have the image hosted somewhere, you may publish a [telegra.ph article](https://telegra.ph) with your image and copy the image address from there.

To know more about the environment variables, check [References](#references).

### For Local Building

1. Clone the repository

   ```sh
   git clone https://github.com/Majeed-GitHub/Birthday-wish
   ```

2. Install dependencies

   ```sh
   npm install
   ```

3. Add a pic of the receiver, in the `./local` directory. Ensure that the image is of 1:1 ratio or it might get cropped and squished.

4. Create a `.env` file in root directory, and add the following lines.

   ```env
    NAME='Name of the Receiever'
    PIC='name-of-image.extension'
   ```

5. Execute the following commands in order.

   ```sh
    npm run init-index-local
    npm run build:parcel
   ```

6. Upon Successful execution, your built files will be ready in the `./dist` directory. Open `./dist/index.html` to see the card.

For further customization, checkout [here](./docs/customizations.md).

---

## References

- [Environment Variables](./docs/variables.md)

- [Attributions](./docs/attributions.md)

---

## Support

If you have any queries or need some help in deployment, you may contact me here

<div align="center">

<a href="https://t.me/facsmiles"><img src="https://cdn.cdnlogo.com/logos/t/39/telegram.svg" height="50px"></a>
<a href="mailto:majeed0611@gmail.com"><img src="https://cdn.cdnlogo.com/logos/g/93/gmail.svg" height="50px"></a>

Made with 💖 by Majeed Shaik

</div>
