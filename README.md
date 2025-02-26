   ## MINISHELL
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
   <div><p>This project is straightforward, yet quite complicated: we are replicating some key features of Bash. No memory leaks. No crashes. </p>

Our goal is to match Bash’s behavior as closely as possible, from exit codes to its small quirks. However, we are not aiming for a full Bash implementation—only specific parts, such as:
<ul>
    <li>Parsing and Tokenization</li>
    <li>Redirections (<code>&lt;</code>, <code>&gt;</code>, <code>&lt;&lt;</code>, <code>&gt;&gt;</code>)</li>
    <li>Pipes (only <code>|</code>)</li>
    <li>Handling environment variables (e.g., <code>$USER</code>, <code>$SOMETHING</code>)</li>
    <li>Handling <code>$?</code> (exit code)</li>
    <li>Handling single and double quotes</li>
    <li>Signal handling (Ctrl+C, Ctrl+D, Ctrl+\)</li>
    <li>Built-in commands (<code>echo</code>, <code>cd</code>, <code>pwd</code>, <code>export</code>, <code>unset</code>, <code>env</code>, <code>exit</code>)</li>
</ul>

   Bash is a highly interconnected system, where each feature depends on others. Even a simple command like echo goes beyond printing text—it must also process flags (echo -n), expand variables (echo $USER), and follow quoting rules (echo '$USER').

With so many layers of complexity, this project really represented a struggle, yet made me learn about various conecpts, and made me feel more confident with my programming.

After many restless days, countless nights with barely any sleep, and a few tears, I am very happy, and proud, to say I've finished this mark in my learning carreer.
</div>
    <div align="center"><img src="https://github.com/user-attachments/assets/1e2e66b6-6da3-4f27-af85-319ce7b553bc" alt="header" width="30%"/></div>
</body>
</html>


