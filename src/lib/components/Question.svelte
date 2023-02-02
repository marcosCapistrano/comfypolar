<script>
// @ts-nocheck

    export let question;
    export let answer;
</script>
<div class="question">
	<span class="question">- {question}</span>
	<p>
        {answer}
	</p>
</div>

<style lang="scss">
    .question {
        margin-top: 1rem;
        margin-bottom: 1rem;

        .question {
            font-size: var(--step-1);
            font-weight: bold;
            font-style: italic;
            margin-bottom: .2em;
            display: block;
        }
    }
</style>
