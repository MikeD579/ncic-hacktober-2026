<template>
    <header>
        <div style="display: flex; gap: 4rem;">
            <div>
                Student Picker
            </div>
            <div>
                back button
            </div>
        </div>
        <div>
            menu
        </div>
    </header>

    <div id="main-content">
        <slot />
    </div>
</template>

<style lang="css" scoped>
header {
    padding: 1rem 4rem;
    display: flex;
    justify-content: space-between;
    gap: 2rem;
}

#main-content {
    padding: 4rem 4rem;
    display: flex;
    flex-direction: column;
    gap: 2rem;
}
</style>
