**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w25-s6.492/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1390-170:11097] *** Process received signal ***
[fv-az1390-170:11097] Signal: Aborted (6)
[fv-az1390-170:11097] Signal code:  (-6)
[fv-az1390-170:11097] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fabf7045330]
[fv-az1390-170:11097] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fabf709eb2c]
[fv-az1390-170:11097] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fabf704527e]
[fv-az1390-170:11097] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fabf70288ff]
[fv-az1390-170:11097] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fabf74a5ff5]
[fv-az1390-170:11097] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fabf74bb0da]
[fv-az1390-170:11097] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fabf74a5a55]
[fv-az1390-170:11097] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fabf74a5a6f]
[fv-az1390-170:11097] [ 8] plumed_master(+0x146dd)[0x55af53c776dd]
[fv-az1390-170:11097] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fabf702a1ca]
[fv-az1390-170:11097] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fabf702a28b]
[fv-az1390-170:11097] [11] plumed_master(+0x15365)[0x55af53c78365]
[fv-az1390-170:11097] *** End of error message ***
</pre>
{% endraw %}
