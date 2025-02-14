# Inefficient useEffect in React Component

This repository demonstrates a common React bug where the `useEffect` hook runs on every render, even when it's meant to only re-run when a specific dependency changes. This can lead to unnecessary re-renders and performance issues. The solution showcases how to correctly use useEffect by specifying dependencies effectively.