**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[pkrvmpptgkbjq6m:10837] *** Process received signal ***
[pkrvmpptgkbjq6m:10837] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10837] Signal code:  (-6)
[pkrvmpptgkbjq6m:10837] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0681645330]
[pkrvmpptgkbjq6m:10837] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f068169eb2c]
[pkrvmpptgkbjq6m:10837] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f068164527e]
[pkrvmpptgkbjq6m:10837] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f06816288ff]
[pkrvmpptgkbjq6m:10837] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0681aa5ff5]
[pkrvmpptgkbjq6m:10837] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0681abb0da]
[pkrvmpptgkbjq6m:10837] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0681aa5a55]
[pkrvmpptgkbjq6m:10837] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0681aa5a6f]
[pkrvmpptgkbjq6m:10837] [ 8] plumed_master(+0x146dd)[0x556c683c76dd]
[pkrvmpptgkbjq6m:10837] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f068162a1ca]
[pkrvmpptgkbjq6m:10837] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f068162a28b]
[pkrvmpptgkbjq6m:10837] [11] plumed_master(+0x15365)[0x556c683c8365]
[pkrvmpptgkbjq6m:10837] *** End of error message ***
</pre>
{% endraw %}
