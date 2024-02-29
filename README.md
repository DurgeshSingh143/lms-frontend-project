# LMS Frontend

### Setup instruction

1. Clone the project
```
   git clone https://github.com/DurgeshSingh143/lms-frontend-project.git
```

2. Move into the directory
```
   cd lms-frontend-project
```

3. install dependencies
```
   npm install
```

4. run the server
```
   npm run dev
```

### Setup instructions for tailwind
[tailwind official instruction doc](https://tailwindcss.com/docs/installation)

1.  Install tailwindcss
```
   npm install -D tailwindcss
```

2. Create tailwind config file
```
   npx tailwindcss init
```

3. Add file extensions to tailwind config file in the contents property
```
   "./src/**/*.{html,js,jsx,ts,tsx}"
```

4. Add the tailwind directives at the top of the `index.css` file
```
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
```