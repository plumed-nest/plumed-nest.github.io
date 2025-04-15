**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w14-s4.116/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1693-957:65832] *** Process received signal ***
[fv-az1693-957:65832] Signal: Aborted (6)
[fv-az1693-957:65832] Signal code:  (-6)
[fv-az1693-957:65832] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f20ac245330]
[fv-az1693-957:65832] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f20ac29eb2c]
[fv-az1693-957:65832] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f20ac24527e]
[fv-az1693-957:65832] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f20ac2288ff]
[fv-az1693-957:65832] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f20ac6a5ff5]
[fv-az1693-957:65832] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f20ac6bb0da]
[fv-az1693-957:65832] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f20ac6a5a55]
[fv-az1693-957:65832] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f20ac6a5a6f]
[fv-az1693-957:65832] [ 8] plumed_master(+0x146dd)[0x55bdfb4746dd]
[fv-az1693-957:65832] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f20ac22a1ca]
[fv-az1693-957:65832] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f20ac22a28b]
[fv-az1693-957:65832] [11] plumed_master(+0x15365)[0x55bdfb475365]
[fv-az1693-957:65832] *** End of error message ***
</pre>
{% endraw %}
