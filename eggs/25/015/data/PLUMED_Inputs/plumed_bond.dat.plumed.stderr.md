**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_bond.dat   
Download: [zipped raw stdout](plumed_bond.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_bond.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "MOLECULES" is not known.
[runnervm0kj6c:04131] *** Process received signal ***
[runnervm0kj6c:04131] Signal: Aborted (6)
[runnervm0kj6c:04131] Signal code:  (-6)
[runnervm0kj6c:04131] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdc77645330]
[runnervm0kj6c:04131] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdc7769eb2c]
[runnervm0kj6c:04131] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdc7764527e]
[runnervm0kj6c:04131] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdc776288ff]
[runnervm0kj6c:04131] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdc77aa5ff5]
[runnervm0kj6c:04131] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdc77abb0da]
[runnervm0kj6c:04131] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdc77aa5a55]
[runnervm0kj6c:04131] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdc77aa5a6f]
[runnervm0kj6c:04131] [ 8] plumed(+0x146dd)[0x56335dd9a6dd]
[runnervm0kj6c:04131] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdc7762a1ca]
[runnervm0kj6c:04131] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdc7762a28b]
[runnervm0kj6c:04131] [11] plumed(+0x15365)[0x56335dd9b365]
[runnervm0kj6c:04131] *** End of error message ***
</pre>
{% endraw %}
