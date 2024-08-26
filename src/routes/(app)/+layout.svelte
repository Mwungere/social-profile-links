<script>
    import '../../styles/globals.css'
</script>
<main>
    <slot></slot>
</main>

<style>
    main{
        width: 500px;
        max-height: fit-content;
        background: hsl(0, 0%, 12%);
        display: flex;
        justify-content: center;
        align-items: center;
        border-radius: 10px;
    }

    @media (max-width:600px){
    main{
      width: 90%;
      
    }
}
</style>