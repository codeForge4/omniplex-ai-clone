import { configureStore } from '@reduxjs/toolkit';
// Import your slices here, for example:
// import userReducer from './features/user/userSlice';

export const store = configureStore({
  reducer: {
    // user: userReducer,
    // Add other slices here
  },
  // You can customize middleware or devTools here if needed
  // middleware: (getDefaultMiddleware) => getDefaultMiddleware(),
  // devTools: process.env.NODE_ENV !== 'production',
});

export type RootState = ReturnType<typeof store.getState>;
export type AppDispatch = typeof store.dispatch;
