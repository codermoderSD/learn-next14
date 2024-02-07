<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>React Refresher</h1>
    <p>Welcome to React Refresher! This is a <a href="https://reactjs.org/">React</a> application</p>
    <h2>Getting Started</h2>
    <h3>Prerequisites</h3>
    <ul>
        <li><a href="https://nodejs.org/">Node.js</a> installed on your machine</li>
        <li><a href="https://www.npmjs.com/">npm</a> or <a href="https://yarnpkg.com/">Yarn</a> package manager</li>
    </ul>
    <h3>Installation</h3>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone https://github.com/codermoderSD/next-14-learnings.git</code></pre>
        <li>Navigate to the project directory:</li>
        <pre><code>cd project-name</code></pre>
        <li>Install dependencies:</li>
        <pre><code>npm install</code></pre>
        <p>or</p>
        <pre><code>yarn</code></pre>
    </ol>
    <h3>Development</h3>
    <p>To start the development server, run:</p>
    <pre><code>npm run dev</code></pre>
    <p>or</p>
    <pre><code>yarn dev</code></pre>
    <p>Open <a href="http://localhost:5173">http://localhost:5173</a> in your browser to view the application.</p>
    <h3>Building for Production</h3>
    <p>To build the application for production, run:</p>
    <pre><code>npm run build</code></pre>
    <p>or</p>
    <pre><code>yarn build</code></pre>
    <p>This will generate an optimized build of your application in the <code>.next</code> directory.</p>
    <h2>Component Structure</h2>
    <ul>
            <li><strong>components/</strong> - Reusable UI components
                <ul>
                    <li><strong>ComponentName/</strong> - Individual component folder
                        <ul>
                            <li><strong>index.jsx</strong> - UI component file</li>
                            <li><strong>service.jsx</strong> - Logic component file</li>
                            <li><strong>utils.jsx</strong> - Utility hooks</li>
                            <li><strong>ComponentName.module.css</strong> - CSS module</li>
                        </ul>
                    </li>
                </ul>
            </li>
</ul>
    <h2>Writing Commit Messages 📝</h2>
    <p>In this project, we adhere to a structured format for writing commit messages. This ensures clarity and consistency across contributions. Below is the recommended format:</p>
    <pre>
Type (Scope): Subject
</pre>
    <h3>Example</h3>
    <pre>
feat(FeatureName): Add new functionality
</pre>
    <h3>Types of Commits</h3>
    <ul>
        <li><strong>feat:</strong> The new feature being added to the application</li>
        <li><strong>fix:</strong> A bug fix (correlates with PATCH in SemVer)</li>
        <li><strong>style:</strong> Feature and updates related to styling</li>
        <li><strong>refactor:</strong> Refactoring a specific section of the codebase</li>
        <li><strong>test:</strong> Everything related to testing</li>
        <li><strong>docs:</strong> Everything related to documentation</li>
        <li><strong>chore:</strong> Regular code maintenance</li>
        <li><strong>wip:</strong> Code that is a work in progress</li>
        <li><strong>feat!:</strong> Breaking change to the codebase</li>
        <li><strong>fix!:</strong> Fixing a bug that is a breaking change</li>
    </ul>
</body>
</html>
