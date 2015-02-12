# alfred-beyondcompare4
Open files in Beyond Compare using Alfred (Mac OSX)

<h3>Install</h3>
Extract the zipfile and execute <code>Beyond Compare 4.alfredworkflow</code>. It will automatically be installed in Alfred.

<h3>Dependencies</h3>
Make sure you have installed the Beyond Compare command line tools.

<h3>System Modifications</h3>
The workflow can create a hidden file in your home directory called .bcleft. When uninstalling this workflow, remove this file manually.

<h3>Usage</h3>
<ul>
<li><p>Open <code>file1</code> in Beyond Compare</p>
<code>bcomp file1</code></li>
<li><p>Select <code>file1</code> for the left panel, and compare it with <code>file2</code2></p>
<code>bcleft file1</code><br/>
<code>bccomp file2</code></li>
</ul>

<h3>Usage as a file action</h3>
<ul>
<li>Select one file and in the File Actions menu choose: <code>Compare with Beyond Compare</code></li>
<li>Select two files (using File Buffer) and in the File Actions menu choose: <code>Compare with Beyond Compare</code></li>
<li>Select one file and in the File Actions menu choose: <code>Left compare with Beyond Compare</code>. Then select a second file and in the File Actions menu choose: <code>Compare with Beyond Compare</code></li>
</ul>

<strong>NOTE:</strong> the two methods of usage can be combined.
