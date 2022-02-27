<script>
	import mreHtml from "./lib/mre.html?raw"
	import mreJs from "./lib/mre.js?url"
	const mre = mreHtml.replace("$lib/mre.js", mreJs)
</script>

<iframe srcdoc={mre} ></iframe>