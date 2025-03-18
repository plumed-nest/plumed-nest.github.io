**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_FM/plumed_FM.dat   
Download: [zipped raw stdout](plumed_FM.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FM.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "FPS" is not known.
[fv-az1267-279:69242] *** Process received signal ***
[fv-az1267-279:69242] Signal: Aborted (6)
[fv-az1267-279:69242] Signal code:  (-6)
[fv-az1267-279:69242] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff184445330]
[fv-az1267-279:69242] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff18449eb2c]
[fv-az1267-279:69242] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff18444527e]
[fv-az1267-279:69242] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff1844288ff]
[fv-az1267-279:69242] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff1848a5ff5]
[fv-az1267-279:69242] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff1848bb0da]
[fv-az1267-279:69242] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff1848a5a55]
[fv-az1267-279:69242] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff1848a5a6f]
[fv-az1267-279:69242] [ 8] plumed(+0x146dd)[0x55aab507a6dd]
[fv-az1267-279:69242] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff18442a1ca]
[fv-az1267-279:69242] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff18442a28b]
[fv-az1267-279:69242] [11] plumed(+0x15365)[0x55aab507b365]
[fv-az1267-279:69242] *** End of error message ***
</pre>
{% endraw %}
