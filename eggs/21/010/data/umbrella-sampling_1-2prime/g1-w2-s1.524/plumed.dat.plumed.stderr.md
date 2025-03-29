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
[fv-az789-879:67387] *** Process received signal ***
[fv-az789-879:67387] Signal: Aborted (6)
[fv-az789-879:67387] Signal code:  (-6)
[fv-az789-879:67387] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3972045330]
[fv-az789-879:67387] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f397209eb2c]
[fv-az789-879:67387] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f397204527e]
[fv-az789-879:67387] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f39720288ff]
[fv-az789-879:67387] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f39724a5ff5]
[fv-az789-879:67387] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f39724bb0da]
[fv-az789-879:67387] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f39724a5a55]
[fv-az789-879:67387] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f39724a5a6f]
[fv-az789-879:67387] [ 8] plumed(+0x146dd)[0x555ec8afa6dd]
[fv-az789-879:67387] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f397202a1ca]
[fv-az789-879:67387] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f397202a28b]
[fv-az789-879:67387] [11] plumed(+0x15365)[0x555ec8afb365]
[fv-az789-879:67387] *** End of error message ***
</pre>
{% endraw %}
