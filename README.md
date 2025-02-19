# React Router v6 Nested Route with Params Bug

This repository demonstrates a bug in React Router v6 where nested routes with parameters fail to render correctly if the parent route doesn't exactly match the URL.  The issue occurs when navigating directly to a nested route with params. The solution involves using the `useParams` hook correctly and ensuring that routes are nested appropriately. 