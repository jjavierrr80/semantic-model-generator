# Admin apps

This folder contains a Streamlit app designed that is designed to help you iterate your semantic models for the Cortex Analyst feature.

The iteration app currently points to an existing semantic model on stage, allow you to chat against it, test the result and modify for verified queries.


<table border="0">
   <tr>
     <td><img src="https://github.com/Snowflake-Labs/semantic-model-generator/assets/103658138/2b5fd664-9a9a-46ed-afbf-cb7638f0ad19" width="700"></td>
     <td><img src="https://github.com/Snowflake-Labs/semantic-model-generator/assets/103658138/d96a4255-9e82-41ba-8a82-dcb87353b667" width="500"></td>
  </tr>
  <tr>
      <td><strong>Iteration app</strong> · so you can iterate on your semantic model by trying it live in a chat UI!</td>
      <td><strong>(coming soon) Builder app</strong> · so you can build your semantic model and edit tables, measures and dimensions from a UI</td>
   </tr>
<table>

## Get started

1. Install all dependencies by running the following Makefile command from the root repo:
```bash
make setup_admin_app
```

2. Inside the `admin_apps/` directory, run the following command:

```bash
streamlit run iteration_app.py  # for the Iteration app
```

Alternatively, you can use the Make target from the root directory:
```bash
make run_admin_app
```

3. Enjoy! 