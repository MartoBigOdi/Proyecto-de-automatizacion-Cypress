# PROYECTO de automation con Cypress

# "scripts": 
#    "open": "cypress open",
#    "test": "cypress run",
#    "testChromeHeaded": "npm run test -- --browser chrome --headed",
#    "testChrome": "npm run test -- --browser chrome --headless",
#    "testDashboardChrome": "npm run test -- --browser chrome --headless --record --key 4df135f1-8343-477e-b328-118f85d5d9d7",
#    "testSpecific": "npm run testChrome --spec .\\cypress\\integration\\2-advanced-examples\\ClothesRetailPage.js"
  
# Para correr un feature con cucumber este es el script
npm run testChromeHeaded --spec cypress\integration\Cucumber\shoppingTest.feature

# Para correr con Tags, script
npx cypress-tags run -e TAGS="@MiTag" --browser chrome