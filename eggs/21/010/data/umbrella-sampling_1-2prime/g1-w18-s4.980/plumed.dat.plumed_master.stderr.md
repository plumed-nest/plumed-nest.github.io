**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w18-s4.980/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1693-957:66039] *** Process received signal ***
[fv-az1693-957:66039] Signal: Aborted (6)
[fv-az1693-957:66039] Signal code:  (-6)
[fv-az1693-957:66039] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbdc9045330]
[fv-az1693-957:66039] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbdc909eb2c]
[fv-az1693-957:66039] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbdc904527e]
[fv-az1693-957:66039] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbdc90288ff]
[fv-az1693-957:66039] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbdc94a5ff5]
[fv-az1693-957:66039] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbdc94bb0da]
[fv-az1693-957:66039] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbdc94a5a55]
[fv-az1693-957:66039] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbdc94a5a6f]
[fv-az1693-957:66039] [ 8] plumed_master(+0x146dd)[0x55774ac616dd]
[fv-az1693-957:66039] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbdc902a1ca]
[fv-az1693-957:66039] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbdc902a28b]
[fv-az1693-957:66039] [11] plumed_master(+0x15365)[0x55774ac62365]
[fv-az1693-957:66039] *** End of error message ***
</pre>
{% endraw %}
