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
[fv-az789-879:67095] *** Process received signal ***
[fv-az789-879:67095] Signal: Aborted (6)
[fv-az789-879:67095] Signal code:  (-6)
[fv-az789-879:67095] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efd56845330]
[fv-az789-879:67095] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efd5689eb2c]
[fv-az789-879:67095] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efd5684527e]
[fv-az789-879:67095] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efd568288ff]
[fv-az789-879:67095] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efd56ca5ff5]
[fv-az789-879:67095] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efd56cbb0da]
[fv-az789-879:67095] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efd56ca5a55]
[fv-az789-879:67095] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efd56ca5a6f]
[fv-az789-879:67095] [ 8] plumed_master(+0x146dd)[0x5576fa8266dd]
[fv-az789-879:67095] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efd5682a1ca]
[fv-az789-879:67095] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efd5682a28b]
[fv-az789-879:67095] [11] plumed_master(+0x15365)[0x5576fa827365]
[fv-az789-879:67095] *** End of error message ***
</pre>
{% endraw %}
