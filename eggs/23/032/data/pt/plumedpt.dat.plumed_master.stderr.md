**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[fv-az1110-827:61083] *** Process received signal ***
[fv-az1110-827:61083] Signal: Aborted (6)
[fv-az1110-827:61083] Signal code:  (-6)
[fv-az1110-827:61083] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7708845330]
[fv-az1110-827:61083] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f770889eb2c]
[fv-az1110-827:61083] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f770884527e]
[fv-az1110-827:61083] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f77088288ff]
[fv-az1110-827:61083] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7708ca5ff5]
[fv-az1110-827:61083] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7708cbb0da]
[fv-az1110-827:61083] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7708ca5a55]
[fv-az1110-827:61083] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7708ca5a6f]
[fv-az1110-827:61083] [ 8] plumed_master(+0x146dd)[0x556d36c876dd]
[fv-az1110-827:61083] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f770882a1ca]
[fv-az1110-827:61083] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f770882a28b]
[fv-az1110-827:61083] [11] plumed_master(+0x15365)[0x556d36c88365]
[fv-az1110-827:61083] *** End of error message ***
</pre>
{% endraw %}
