- Many of the json dependencies were very depreciated and were not initially supported at npm install. Particularly this line of code "import {BrowserRouter, Routes, Route} from "react-router-dom";" on the first line of App.jsx.
- npm audit fix --force is required after npm install to fix all risks and dependency errors

- Icons were found at: https://cdn-icons-png.flaticon.com
- Almost all CSS was generated for a more cohesive theme.
- nanoid/UUID: YouTube
- Router file issues resolved with AI when streamlining functionality (consolidating ConstructionPage.jsx with SpacecraftForm.jsx due to similar functionality, Form was moved to a page for construct page to work)
