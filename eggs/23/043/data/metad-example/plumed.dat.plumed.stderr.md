**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[pkrvmpptgkbjq6m:08358] *** Process received signal ***
[pkrvmpptgkbjq6m:08358] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08358] Signal code:  (-6)
[pkrvmpptgkbjq6m:08358] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3305645330]
[pkrvmpptgkbjq6m:08358] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f330569eb2c]
[pkrvmpptgkbjq6m:08358] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f330564527e]
[pkrvmpptgkbjq6m:08358] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f33056288ff]
[pkrvmpptgkbjq6m:08358] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3305aa5ff5]
[pkrvmpptgkbjq6m:08358] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3305abb0da]
[pkrvmpptgkbjq6m:08358] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3305aa5a55]
[pkrvmpptgkbjq6m:08358] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3305aa5a6f]
[pkrvmpptgkbjq6m:08358] [ 8] plumed(+0x146dd)[0x56010ce366dd]
[pkrvmpptgkbjq6m:08358] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f330562a1ca]
[pkrvmpptgkbjq6m:08358] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f330562a28b]
[pkrvmpptgkbjq6m:08358] [11] plumed(+0x15365)[0x56010ce37365]
[pkrvmpptgkbjq6m:08358] *** End of error message ***
</pre>
{% endraw %}
