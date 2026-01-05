# Simplify Frontend – React Native (Expo)

This project is a React Native frontend application built using **Expo**.  
Below are the **exact commands** used to run this project, along with a clear explanation of what each command does.

---

## ▶️ How to Run the Project

Follow the commands in the given order:

---

npm init 
npm install 
npx expo install @expo/metro-runtime  #Installs Metro bundler runtime used by Expo
npm run dev


# note(Add this exact below line in MetalPriceApp-Web/src/utils/constants.js to see price of silver,platinum, etc)
export const METALS = [
  { name: "Gold", code: "XAU" },
  { name: "Silver", code: "XAG" },
  { name: "Platinum", code: "XPT" },
  { name: "Palladium", code: "XPD" },
];
