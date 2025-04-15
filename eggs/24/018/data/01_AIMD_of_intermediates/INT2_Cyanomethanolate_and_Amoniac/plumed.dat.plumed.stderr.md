**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_Cyanomethanolate_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1693-957:62176] *** Process received signal ***
[fv-az1693-957:62176] Signal: Aborted (6)
[fv-az1693-957:62176] Signal code:  (-6)
[fv-az1693-957:62176] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f58a6445330]
[fv-az1693-957:62176] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f58a649eb2c]
[fv-az1693-957:62176] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f58a644527e]
[fv-az1693-957:62176] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f58a64288ff]
[fv-az1693-957:62176] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f58a68a5ff5]
[fv-az1693-957:62176] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f58a68bb0da]
[fv-az1693-957:62176] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f58a68a5a55]
[fv-az1693-957:62176] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f58a68a5a6f]
[fv-az1693-957:62176] [ 8] plumed(+0x146dd)[0x56123cbf76dd]
[fv-az1693-957:62176] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f58a642a1ca]
[fv-az1693-957:62176] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f58a642a28b]
[fv-az1693-957:62176] [11] plumed(+0x15365)[0x56123cbf8365]
[fv-az1693-957:62176] *** End of error message ***
</pre>
{% endraw %}
