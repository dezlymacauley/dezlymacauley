<!---------------------------------------------------------------------------->
<!-- SECTION: Custom Class Attributes -->

<style>

    .centered-title {
        text-align: center;
    }

    .title-content {
        font-weight: 800;
    }

    .group-of-tech-category-containers {
        display: flex;
        flex-direction: row;
        gap: 5px;
        margin-bottom: 5px;
    }

    .tech-category-container {
        display: flex;
        flex-direction: column;
        gap: 4px;
        justify-content: center; /* Centers elements vertically (in column direction) */
        align-items: center;     /* Centers elements horizontally */
        border-width: 2px; 
        border-style: solid;
        border-color: purple; 
        padding-left: 10px;
        padding-right:10px;
        padding-bottom: 10px;
    }

    .tech-image-container {
        display: flex;
        flex-direction: row;
        gap: 2px;
    }

    .tech-text-container {
        display: flex;
        flex-direction: column;
    }

    .tech-name {
        font-weight: 500;
        font-size: 18px;
    }

</style>

<!---------------------------------------------------------------------------->
<!-- SECTION: README Content -->

<!-- Title -->
<h1 class="centered-title">
    <p class="title-content">😈 Dezly Macauley</p>
</h1>

<!---------------------------------------------------------------------------->

<div class="group-of-tech-category-containers">
    <!-- Low-Level Programming -->
    <div class="tech-category-container">
        <h3>Linux Proficiency</h3>
        <div class="tech-image-container">
            <img src="images/arch_linux.png" alt="Rust Logo" width="50" height="50">
        </div>
        <div class="tech-text-container">
            <span class="tech-name">Arch</span>
        </div>
    </div>
    <!-- Low-Level Programming -->
    <div class="tech-category-container">
        <h3>Low-Level Programming</h3>
        <div class="tech-image-container">
            <img src="images/rust.png" alt="Rust Logo" width="50" height="50">
            <img src="images/c.png" alt="Rust Logo" width="50" height="50">
        </div>
        <div class="tech-text-container">
            <span class="tech-name">Rust, C</span>
        </div>
    </div>
</div>

<!---------------------------------------------------------------------------->

<div class="group-of-tech-category-containers">
    <!-- Database Development -->
    <div class="tech-category-container">
        <h3>Database Development</h3>
        <div class="tech-image-container">
            <img src="images/postgresql.png" alt="Rust Logo" width="50" height="50">
            <img src="images/sqlite.png" alt="Rust Logo" width="50" height="50">
        </div>
        <div class="tech-text-container">
            <span class="tech-name">PostgreSQL, SQLite</span>
        </div>
    </div>
    <!-- Back-End Programming -->
    <div class="tech-category-container">
        <h3>Back-End Development</h3>
        <div class="tech-image-container">
            <img src="images/go.png" alt="Rust Logo" width="50" height="50">
            <img src="images/python.png" alt="Rust Logo" width="50" height="50">
        </div>
        <div class="tech-text-container">
            <span class="tech-name">Go, Python</span>
        </div>
    </div>
</div>

<!---------------------------------------------------------------------------->

<div class="group-of-tech-category-containers">
    <!-- Smart Contract Development -->
    <div class="tech-category-container">
        <h3>Smart Contract Development</h3>
        <div class="tech-image-container">
            <img src="images/vyper.png" alt="Rust Logo" width="50" height="50">
        </div>
        <div class="tech-text-container">
            <span class="tech-name">Vyper</span>
        </div>
    </div>
</div>
<!---------------------------------------------------------------------------->
