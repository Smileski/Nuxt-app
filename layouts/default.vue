<template>
    <div>
        <header>
            <nav>
                <ul>
                    <li>
                        <NuxtLink to="/about">About</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/america">America</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/africa">Africa</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/blog">Blog</NuxtLink>
                    </li>
                </ul>
            </nav>
        </header>
        <slot />
    </div>  
</template>

<style scoped>
    nav {
    background-color: #f2f2f2;
    padding: 10px;
}

ul  {
    list-style-type: none;
    display: flex;
    justify-content: start;    
    gap: 12px;
}

li {
    margin-right: 10px;
}

NextLink {
    text-decoration: none;
    color: #3333;
    font-weight: bold;
}

NextLink.active {
    color: #ff0000;
}

</style>