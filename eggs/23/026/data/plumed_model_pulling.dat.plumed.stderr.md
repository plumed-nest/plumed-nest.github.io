**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1112-175:61545] *** Process received signal ***
[fv-az1112-175:61545] Signal: Aborted (6)
[fv-az1112-175:61545] Signal code:  (-6)
[fv-az1112-175:61545] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f181dc45330]
[fv-az1112-175:61545] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f181dc9eb2c]
[fv-az1112-175:61545] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f181dc4527e]
[fv-az1112-175:61545] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f181dc288ff]
[fv-az1112-175:61545] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f181e0a5ff5]
[fv-az1112-175:61545] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f181e0bb0da]
[fv-az1112-175:61545] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f181e0a5a55]
[fv-az1112-175:61545] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f181e0a5a6f]
[fv-az1112-175:61545] [ 8] plumed(+0x146dd)[0x55759949b6dd]
[fv-az1112-175:61545] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f181dc2a1ca]
[fv-az1112-175:61545] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f181dc2a28b]
[fv-az1112-175:61545] [11] plumed(+0x15365)[0x55759949c365]
[fv-az1112-175:61545] *** End of error message ***
</pre>
{% endraw %}
