**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/di_pept/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1050-229:65699] *** Process received signal ***
[fv-az1050-229:65699] Signal: Aborted (6)
[fv-az1050-229:65699] Signal code:  (-6)
[fv-az1050-229:65699] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6a44445330]
[fv-az1050-229:65699] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6a4449eb2c]
[fv-az1050-229:65699] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6a4444527e]
[fv-az1050-229:65699] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6a444288ff]
[fv-az1050-229:65699] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6a448a5ff5]
[fv-az1050-229:65699] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6a448bb0da]
[fv-az1050-229:65699] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6a448a5a55]
[fv-az1050-229:65699] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6a448a5a6f]
[fv-az1050-229:65699] [ 8] plumed_master(+0x146dd)[0x5625f49236dd]
[fv-az1050-229:65699] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6a4442a1ca]
[fv-az1050-229:65699] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6a4442a28b]
[fv-az1050-229:65699] [11] plumed_master(+0x15365)[0x5625f4924365]
[fv-az1050-229:65699] *** End of error message ***
</pre>
{% endraw %}
