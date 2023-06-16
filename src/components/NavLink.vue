<script>
    export default{
        name: 'Navlink',
        props:[
            'linkElement'
        ]
}
</script>

<template>
    <header>
        <nav>
            <ul>
                <li>
                    {{ linkElement.text }}
                </li>
            </ul>
        </nav>

    </header>
</template>

<style>

</style>