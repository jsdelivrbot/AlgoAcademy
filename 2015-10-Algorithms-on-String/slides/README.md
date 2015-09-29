<!-- section start -->

<!-- attr: {id: 'title', class: 'slide-title', hasScriptWrapper: true} -->
# Algorithms on Strings
## Subtitle
<div class="signature">
	<p class="signature-course">Algorithms on Strings</p>
	<p class="signature-initiative">Telerik Algo Academy</p>
	<a href="http://academy.telerik.com" class="signature-link">http://academy.telerik.com</a>
</div>

<!-- section start -->

<!-- attr: {id: 'table-of-contents'} -->
# Table of Contents
* Parsing
	* Pattern matching
* Searching algorithms
	* Naive string search
	* Rabin-Karp
	* Knuth-Morris-Pratt
	* Aho-Corasick
	* Suffix trees/arrays

<!-- section start -->

<!-- attr: {class: 'slide-section'} -->
# Searching algorithms
## Subtitle

<!-- section start -->

<!-- attr: {} -->
# Naive search
* Test for match at every possible position
	* Simple but inefficient
	* Quadratic in time

<!-- section start -->

<!-- attr: {} -->
# Rabin-Karp
* Uses rolling hash
	* Linear in time
		* Quadratic if you check for collisions
* Capable of multiple pattern search

<!-- attr: {showInPresentation: true} -->
<!-- # Rabin-Karp -->
* **TODO**

<!-- section start -->

<!-- attr: {} -->
# Knuth-Morris-Pratt
* Makes use of previous match info
	* "Partial match" table is precomputed
		* Linear in time
	* Unneeded checks are skipped
	* Linear in time

<!-- section start -->

<!-- attr: {} -->
# Aho-Corasick
* Like KMP, but for multiple patters
	* "Partial match" prefix tree is precomputed
	* Each occurrence of each pattern is found
	* Linear in time
		* There can be quadratic number of occurrences

<!-- section start -->

<!-- attr: {} -->
# Suffix trees
* **TODO**

<!-- attr: {} -->
# Suffix arrays
* **TODO**

<!-- section start -->

<!-- attr: {class: 'slide-questions', id: 'questions'}  -->
# Algorithms on Strings
## Questions