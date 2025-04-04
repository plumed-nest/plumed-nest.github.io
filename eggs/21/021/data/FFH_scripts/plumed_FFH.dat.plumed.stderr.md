**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  FFH_scripts/plumed_FFH.dat   
Download: [zipped raw stdout](plumed_FFH.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FFH.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1695-570:10735] *** Process received signal ***
[fv-az1695-570:10735] Signal: Aborted (6)
[fv-az1695-570:10735] Signal code:  (-6)
[fv-az1695-570:10735] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f082d245330]
[fv-az1695-570:10735] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f082d29eb2c]
[fv-az1695-570:10735] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f082d24527e]
[fv-az1695-570:10735] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f082d2288ff]
[fv-az1695-570:10735] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f082d6a5ff5]
[fv-az1695-570:10735] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f082d6bb0da]
[fv-az1695-570:10735] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f082d6a5a55]
[fv-az1695-570:10735] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f082d6a5a6f]
[fv-az1695-570:10735] [ 8] plumed(+0x146dd)[0x558041c096dd]
[fv-az1695-570:10735] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f082d22a1ca]
[fv-az1695-570:10735] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f082d22a28b]
[fv-az1695-570:10735] [11] plumed(+0x15365)[0x558041c0a365]
[fv-az1695-570:10735] *** End of error message ***
</pre>
{% endraw %}
