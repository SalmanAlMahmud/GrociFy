# 🛒 Grocify

Grocify is a modern grocery shopping application built with Expo React Native. The project uses Clerk authentication, Expo Router, NativeWind, and TypeScript to provide a smooth and secure shopping experience.

## 🚀 Tech Stack

- Expo SDK 57
- React Native
- Expo Router
- TypeScript
- Clerk Authentication
- NativeWind
- Sentry
- React Native Keyboard Controller

## 📦 Getting Started

### 1. Install dependencies

```bash
npm install
```

### 2. Configure environment variables

Create a `.env` file in the project root and add the required Clerk and Sentry keys.

Example:

```env
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=your_publishable_key
CLERK_SECRET_KEY=your_secret_key
EXPO_PUBLIC_SENTRY_DSN=your_sentry_dsn
```

### 3. Start the development server

```bash
npx expo start
```

For Android Development Build:

```bash
npx expo run:android
```

## 📁 Project Structure

```
src/
 └── app/
      ├── _layout.tsx
      ├── index.tsx
      ├── sso-callback.tsx
      └── (auth)/
            ├── _layout.tsx
            └── sign-in.tsx
```

## 👨‍💻 Authors

- Salman Al Mahmud
- Simanta Das
- Wasik Imam
- Priyanka Das
- Azrin Hossain  Adiba
- Suraiya Rahman Etu

---

Built with ❤️ using Expo & React Native.