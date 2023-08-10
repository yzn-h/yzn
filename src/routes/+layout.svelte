<script>
    import "../app.css";
  </script>
  
  <slot />

  <style lang="postcss">
            :global(html) {
      background-color: theme(colors.gray.100);
    color: theme(colors.gray.950);

    }
    @media (prefers-color-scheme: dark){
        :global(html) {
      background-color: theme(colors.gray.950);
    color: theme(colors.gray.50);
    }
    }
    
  </style>