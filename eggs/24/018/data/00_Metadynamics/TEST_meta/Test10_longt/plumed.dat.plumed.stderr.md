**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1693-957:61504] *** Process received signal ***
[fv-az1693-957:61504] Signal: Aborted (6)
[fv-az1693-957:61504] Signal code:  (-6)
[fv-az1693-957:61504] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9b9d045330]
[fv-az1693-957:61504] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9b9d09eb2c]
[fv-az1693-957:61504] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9b9d04527e]
[fv-az1693-957:61504] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9b9d0288ff]
[fv-az1693-957:61504] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9b9d4a5ff5]
[fv-az1693-957:61504] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9b9d4bb0da]
[fv-az1693-957:61504] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9b9d4a5a55]
[fv-az1693-957:61504] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9b9d4a5a6f]
[fv-az1693-957:61504] [ 8] plumed(+0x146dd)[0x55a973c746dd]
[fv-az1693-957:61504] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9b9d02a1ca]
[fv-az1693-957:61504] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9b9d02a28b]
[fv-az1693-957:61504] [11] plumed(+0x15365)[0x55a973c75365]
[fv-az1693-957:61504] *** End of error message ***
</pre>
{% endraw %}
