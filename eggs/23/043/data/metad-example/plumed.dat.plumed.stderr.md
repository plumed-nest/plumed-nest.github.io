**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[fv-az1781-652:62410] *** Process received signal ***
[fv-az1781-652:62410] Signal: Aborted (6)
[fv-az1781-652:62410] Signal code:  (-6)
[fv-az1781-652:62410] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f187d845330]
[fv-az1781-652:62410] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f187d89eb2c]
[fv-az1781-652:62410] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f187d84527e]
[fv-az1781-652:62410] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f187d8288ff]
[fv-az1781-652:62410] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f187dca5ff5]
[fv-az1781-652:62410] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f187dcbb0da]
[fv-az1781-652:62410] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f187dca5a55]
[fv-az1781-652:62410] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f187dca5a6f]
[fv-az1781-652:62410] [ 8] plumed(+0x146dd)[0x560ca57476dd]
[fv-az1781-652:62410] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f187d82a1ca]
[fv-az1781-652:62410] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f187d82a28b]
[fv-az1781-652:62410] [11] plumed(+0x15365)[0x560ca5748365]
[fv-az1781-652:62410] *** End of error message ***
</pre>
{% endraw %}
