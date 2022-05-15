
# A Python REPL to play with Python


Have you found yourself needing an impromptu Python REPL to play with things,
but firing up your scratch conda environment was too much of a hassle?
I've found myself in that situation many times.
I built this HTML page so that I could just quickly test code logic interactively.


<script defer src="https://pyscript.net/unstable/pyscript.js"></script>

<div>
<py-repl output="repl">
from random import choice
choices = "ABC"
choice(choices)
</py-repl>
</div>

<div><pre id="repl"></pre></div>
