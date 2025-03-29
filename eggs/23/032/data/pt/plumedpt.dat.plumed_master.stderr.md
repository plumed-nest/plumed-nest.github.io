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
[fv-az1344-582:61189] *** Process received signal ***
[fv-az1344-582:61189] Signal: Aborted (6)
[fv-az1344-582:61189] Signal code:  (-6)
[fv-az1344-582:61189] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f24de045330]
[fv-az1344-582:61189] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f24de09eb2c]
[fv-az1344-582:61189] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f24de04527e]
[fv-az1344-582:61189] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f24de0288ff]
[fv-az1344-582:61189] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f24de4a5ff5]
[fv-az1344-582:61189] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f24de4bb0da]
[fv-az1344-582:61189] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f24de4a5a55]
[fv-az1344-582:61189] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f24de4a5a6f]
[fv-az1344-582:61189] [ 8] plumed_master(+0x146dd)[0x55bd5621b6dd]
[fv-az1344-582:61189] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f24de02a1ca]
[fv-az1344-582:61189] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f24de02a28b]
[fv-az1344-582:61189] [11] plumed_master(+0x15365)[0x55bd5621c365]
[fv-az1344-582:61189] *** End of error message ***
</pre>
{% endraw %}
