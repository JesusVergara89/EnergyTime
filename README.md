# React + TypeScript + Vite

# EnergyTime

**EnergyTime** es líder en el campo de la energía solar y renovable. Nos especializamos en ofrecer soluciones completas que abarcan desde la planificación y diseño hasta la construcción y operación de proyectos solares.

![EnergyTime Logo](/src/images/Energytime.png)

Nuestros servicios incluyen la elaboración de presupuestos precisos y competitivos, el diseño eficiente de instalaciones y la implementación de tecnologías avanzadas para maximizar el rendimiento energético.

![Servicios de EnergyTime](/src/images/Services.png)

Además, proporcionamos equipos de alta calidad y ofrecemos consultoría estratégica para garantizar el éxito de cada proyecto solar.

En **EnergyTime**, trabajamos de cerca con nuestros clientes para hacer realidad sus proyectos de energía solar, contribuyendo así a un futuro más limpio y sostenible.

![Futuro Sostenible](images/energytime_future.png)





- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
