**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w19-s5.196/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az2209-645:65624] *** Process received signal ***
[fv-az2209-645:65624] Signal: Aborted (6)
[fv-az2209-645:65624] Signal code:  (-6)
[fv-az2209-645:65624] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f21dcc45330]
[fv-az2209-645:65624] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f21dcc9eb2c]
[fv-az2209-645:65624] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f21dcc4527e]
[fv-az2209-645:65624] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f21dcc288ff]
[fv-az2209-645:65624] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f21dd0a5ff5]
[fv-az2209-645:65624] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f21dd0bb0da]
[fv-az2209-645:65624] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f21dd0a5a55]
[fv-az2209-645:65624] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f21dd0a5a6f]
[fv-az2209-645:65624] [ 8] plumed(+0x146dd)[0x55f9e78b06dd]
[fv-az2209-645:65624] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f21dcc2a1ca]
[fv-az2209-645:65624] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f21dcc2a28b]
[fv-az2209-645:65624] [11] plumed(+0x15365)[0x55f9e78b1365]
[fv-az2209-645:65624] *** End of error message ***
</pre>
{% endraw %}
