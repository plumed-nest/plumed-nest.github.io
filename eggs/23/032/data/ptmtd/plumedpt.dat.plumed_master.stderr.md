**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[fv-az1665-105:06156] *** Process received signal ***
[fv-az1665-105:06156] Signal: Aborted (6)
[fv-az1665-105:06156] Signal code:  (-6)
[fv-az1665-105:06156] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fccdd845330]
[fv-az1665-105:06156] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fccdd89eb2c]
[fv-az1665-105:06156] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fccdd84527e]
[fv-az1665-105:06156] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fccdd8288ff]
[fv-az1665-105:06156] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fccddca5ff5]
[fv-az1665-105:06156] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fccddcbb0da]
[fv-az1665-105:06156] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fccddca5a55]
[fv-az1665-105:06156] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fccddca5a6f]
[fv-az1665-105:06156] [ 8] plumed_master(+0x146dd)[0x55bf9fbfa6dd]
[fv-az1665-105:06156] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fccdd82a1ca]
[fv-az1665-105:06156] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fccdd82a28b]
[fv-az1665-105:06156] [11] plumed_master(+0x15365)[0x55bf9fbfb365]
[fv-az1665-105:06156] *** End of error message ***
</pre>
{% endraw %}
