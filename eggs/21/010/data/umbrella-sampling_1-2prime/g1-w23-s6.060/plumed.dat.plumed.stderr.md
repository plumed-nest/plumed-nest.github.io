**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w23-s6.060/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az789-879:67593] *** Process received signal ***
[fv-az789-879:67593] Signal: Aborted (6)
[fv-az789-879:67593] Signal code:  (-6)
[fv-az789-879:67593] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8290845330]
[fv-az789-879:67593] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f829089eb2c]
[fv-az789-879:67593] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f829084527e]
[fv-az789-879:67593] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f82908288ff]
[fv-az789-879:67593] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8290ca5ff5]
[fv-az789-879:67593] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8290cbb0da]
[fv-az789-879:67593] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8290ca5a55]
[fv-az789-879:67593] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8290ca5a6f]
[fv-az789-879:67593] [ 8] plumed(+0x146dd)[0x55bba80786dd]
[fv-az789-879:67593] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f829082a1ca]
[fv-az789-879:67593] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f829082a28b]
[fv-az789-879:67593] [11] plumed(+0x15365)[0x55bba8079365]
[fv-az789-879:67593] *** End of error message ***
</pre>
{% endraw %}
