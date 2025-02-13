**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_FM/plumed_FM.dat   
Download: [zipped raw stdout](plumed_FM.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_FM.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "FPS" is not known.
[fv-az1665-105:15377] *** Process received signal ***
[fv-az1665-105:15377] Signal: Aborted (6)
[fv-az1665-105:15377] Signal code:  (-6)
[fv-az1665-105:15377] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8aa3845330]
[fv-az1665-105:15377] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8aa389eb2c]
[fv-az1665-105:15377] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8aa384527e]
[fv-az1665-105:15377] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8aa38288ff]
[fv-az1665-105:15377] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8aa3ca5ff5]
[fv-az1665-105:15377] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8aa3cbb0da]
[fv-az1665-105:15377] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8aa3ca5a55]
[fv-az1665-105:15377] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8aa3ca5a6f]
[fv-az1665-105:15377] [ 8] plumed_master(+0x146dd)[0x562c1643c6dd]
[fv-az1665-105:15377] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8aa382a1ca]
[fv-az1665-105:15377] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8aa382a28b]
[fv-az1665-105:15377] [11] plumed_master(+0x15365)[0x562c1643d365]
[fv-az1665-105:15377] *** End of error message ***
</pre>
{% endraw %}
