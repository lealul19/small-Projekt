<script>
    export let title = "Lea's small-Projekt";
    import "./app.css"; 
    let inputText = ""; 
</script>

<nav class="navbar">
    <h1>{title}</h1>
    
</nav>

<div class="container">
    <div class="box">
        <h2>Welcome to {title}</h2>
        <input type="text" bind:value={inputText} placeholder="Type something..." />
        <div class="display">
            <h1>{inputText}</h1>
            
        </div>
    </div>
</div>

<footer class="footer">
    <p>&copy; 2025 small-Projekt. All rights reserved.</p>
</footer>
