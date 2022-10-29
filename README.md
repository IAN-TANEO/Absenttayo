<body>
    <div class="wrapper">
        <div class="container">
            <p class="ques" id="ques">Mahal mo na ba ako?</p>
            <button class="yes" id="yes">Yes</button>
            <button class="no" id="no">No</button>
        </div>
    </div>
</body>
<script>
    let no = document.getElementById('no');
    let position;
    no.addEventListener("mouseover", () => {
        position = position ? 0 : 100;
        no.style.transform = 'translate(' + position + 'px,0px)';
    });
    let yes = document.getElementById('yes');
    yes.addEventListener("click", () => {
        ques.innerHTML = "I love you too<3"
    })
</script>
</html>
