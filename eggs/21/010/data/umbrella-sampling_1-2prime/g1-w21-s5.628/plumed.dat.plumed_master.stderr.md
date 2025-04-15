**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w21-s5.628/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1693-957:66247] *** Process received signal ***
[fv-az1693-957:66247] Signal: Aborted (6)
[fv-az1693-957:66247] Signal code:  (-6)
[fv-az1693-957:66247] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f35b6445330]
[fv-az1693-957:66247] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f35b649eb2c]
[fv-az1693-957:66247] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f35b644527e]
[fv-az1693-957:66247] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f35b64288ff]
[fv-az1693-957:66247] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f35b68a5ff5]
[fv-az1693-957:66247] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f35b68bb0da]
[fv-az1693-957:66247] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f35b68a5a55]
[fv-az1693-957:66247] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f35b68a5a6f]
[fv-az1693-957:66247] [ 8] plumed_master(+0x146dd)[0x5598de67c6dd]
[fv-az1693-957:66247] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f35b642a1ca]
[fv-az1693-957:66247] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f35b642a28b]
[fv-az1693-957:66247] [11] plumed_master(+0x15365)[0x5598de67d365]
[fv-az1693-957:66247] *** End of error message ***
</pre>
{% endraw %}
