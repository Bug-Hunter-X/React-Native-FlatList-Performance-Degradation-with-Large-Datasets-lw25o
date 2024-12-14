# React Native FlatList Performance Optimization

This repository demonstrates a common performance issue in React Native's FlatList component when dealing with large datasets and complex item rendering. The `bug.js` file showcases the problematic code, while `bugSolution.js` provides an optimized solution.

**Problem:** Slow scrolling and janky performance due to inefficient rendering and unnecessary re-renders in the FlatList.

**Solution:** Optimizations include using `keyExtractor`, `ItemSeparatorComponent`, and memoization techniques to improve rendering efficiency and reduce unnecessary re-renders.  More advanced solutions may involve using libraries like `react-native-fast-image` for image loading or exploring virtualization techniques for extremely large lists.