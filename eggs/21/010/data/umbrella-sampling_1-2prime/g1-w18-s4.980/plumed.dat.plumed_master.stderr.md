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
[fv-az1390-170:10681] *** Process received signal ***
[fv-az1390-170:10681] Signal: Aborted (6)
[fv-az1390-170:10681] Signal code:  (-6)
[fv-az1390-170:10681] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9323a45330]
[fv-az1390-170:10681] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9323a9eb2c]
[fv-az1390-170:10681] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9323a4527e]
[fv-az1390-170:10681] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9323a288ff]
[fv-az1390-170:10681] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9323ea5ff5]
[fv-az1390-170:10681] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9323ebb0da]
[fv-az1390-170:10681] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9323ea5a55]
[fv-az1390-170:10681] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9323ea5a6f]
[fv-az1390-170:10681] [ 8] plumed_master(+0x146dd)[0x55beb933e6dd]
[fv-az1390-170:10681] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9323a2a1ca]
[fv-az1390-170:10681] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9323a2a28b]
[fv-az1390-170:10681] [11] plumed_master(+0x15365)[0x55beb933f365]
[fv-az1390-170:10681] *** End of error message ***
</pre>
{% endraw %}
