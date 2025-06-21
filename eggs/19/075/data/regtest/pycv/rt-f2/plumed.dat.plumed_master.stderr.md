**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[pkrvmxyh4eaekms:11408] *** Process received signal ***
[pkrvmxyh4eaekms:11408] Signal: Aborted (6)
[pkrvmxyh4eaekms:11408] Signal code:  (-6)
[pkrvmxyh4eaekms:11408] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fee54a45330]
[pkrvmxyh4eaekms:11408] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fee54a9eb2c]
[pkrvmxyh4eaekms:11408] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fee54a4527e]
[pkrvmxyh4eaekms:11408] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fee54a288ff]
[pkrvmxyh4eaekms:11408] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fee54ea5ff5]
[pkrvmxyh4eaekms:11408] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fee54ebb0da]
[pkrvmxyh4eaekms:11408] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fee54ea5a55]
[pkrvmxyh4eaekms:11408] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fee54ea5a6f]
[pkrvmxyh4eaekms:11408] [ 8] plumed_master(+0x146dd)[0x562c9b8dd6dd]
[pkrvmxyh4eaekms:11408] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fee54a2a1ca]
[pkrvmxyh4eaekms:11408] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fee54a2a28b]
[pkrvmxyh4eaekms:11408] [11] plumed_master(+0x15365)[0x562c9b8de365]
[pkrvmxyh4eaekms:11408] *** End of error message ***
</pre>
{% endraw %}
