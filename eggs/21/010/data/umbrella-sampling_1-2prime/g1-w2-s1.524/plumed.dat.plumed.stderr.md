**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w2-s1.524/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1693-957:66127] *** Process received signal ***
[fv-az1693-957:66127] Signal: Aborted (6)
[fv-az1693-957:66127] Signal code:  (-6)
[fv-az1693-957:66127] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa2d0245330]
[fv-az1693-957:66127] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa2d029eb2c]
[fv-az1693-957:66127] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa2d024527e]
[fv-az1693-957:66127] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa2d02288ff]
[fv-az1693-957:66127] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa2d06a5ff5]
[fv-az1693-957:66127] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa2d06bb0da]
[fv-az1693-957:66127] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa2d06a5a55]
[fv-az1693-957:66127] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa2d06a5a6f]
[fv-az1693-957:66127] [ 8] plumed(+0x146dd)[0x556b5b44c6dd]
[fv-az1693-957:66127] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa2d022a1ca]
[fv-az1693-957:66127] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa2d022a28b]
[fv-az1693-957:66127] [11] plumed(+0x15365)[0x556b5b44d365]
[fv-az1693-957:66127] *** End of error message ***
</pre>
{% endraw %}
