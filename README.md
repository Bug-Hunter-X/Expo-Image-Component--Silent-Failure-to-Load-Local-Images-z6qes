# Expo Image Component: Silent Failure to Load Local Images

This repository demonstrates a bug where Expo's `Image` component fails to load local images without providing a clear error message. The issue is particularly frustrating because debugging the problem requires significant effort.  The example shows how this can occur even when the image path appears correct.

**To reproduce:** Run the `bug.js` file.  You'll notice the image fails to load; there's no helpful console error to guide debugging.

**Solution:** The `bugSolution.js` file provides a robust solution involving thorough error handling and path verification. This ensures the app gracefully handles image loading failures and provides better user feedback.

This issue highlights the importance of adding robust error handling when working with assets in React Native applications.