**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w15-s4.332/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1693-957:65884] *** Process received signal ***
[fv-az1693-957:65884] Signal: Aborted (6)
[fv-az1693-957:65884] Signal code:  (-6)
[fv-az1693-957:65884] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f131b245330]
[fv-az1693-957:65884] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f131b29eb2c]
[fv-az1693-957:65884] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f131b24527e]
[fv-az1693-957:65884] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f131b2288ff]
[fv-az1693-957:65884] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f131b6a5ff5]
[fv-az1693-957:65884] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f131b6bb0da]
[fv-az1693-957:65884] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f131b6a5a55]
[fv-az1693-957:65884] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f131b6a5a6f]
[fv-az1693-957:65884] [ 8] plumed_master(+0x146dd)[0x55b719bdd6dd]
[fv-az1693-957:65884] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f131b22a1ca]
[fv-az1693-957:65884] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f131b22a28b]
[fv-az1693-957:65884] [11] plumed_master(+0x15365)[0x55b719bde365]
[fv-az1693-957:65884] *** End of error message ***
</pre>
{% endraw %}
