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
[fv-az1665-105:06103] *** Process received signal ***
[fv-az1665-105:06103] Signal: Aborted (6)
[fv-az1665-105:06103] Signal code:  (-6)
[fv-az1665-105:06103] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe46be45330]
[fv-az1665-105:06103] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe46be9eb2c]
[fv-az1665-105:06103] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe46be4527e]
[fv-az1665-105:06103] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe46be288ff]
[fv-az1665-105:06103] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe46c2a5ff5]
[fv-az1665-105:06103] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe46c2bb0da]
[fv-az1665-105:06103] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe46c2a5a55]
[fv-az1665-105:06103] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe46c2a5a6f]
[fv-az1665-105:06103] [ 8] plumed_master(+0x146dd)[0x5621ec0b16dd]
[fv-az1665-105:06103] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe46be2a1ca]
[fv-az1665-105:06103] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe46be2a28b]
[fv-az1665-105:06103] [11] plumed_master(+0x15365)[0x5621ec0b2365]
[fv-az1665-105:06103] *** End of error message ***
</pre>
{% endraw %}
