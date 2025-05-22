<script>
    
    let totalLines = 9;
    let pattern = '';

    for (let i = 0; i < totalLines; i++) 
    {
        let stars;
        if (i < 5) {
        // First half (5 to 1 stars)
        stars = 5 - i;
        } else {
        // Second half (2 to 5 stars)
        stars = i - 3;
        }
        pattern += '*'.repeat(stars) + '<br>';


    }

    document.write(pattern);
   


</script>
