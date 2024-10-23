**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[fv-az1442-469:08202] *** Process received signal ***
[fv-az1442-469:08202] Signal: Aborted (6)
[fv-az1442-469:08202] Signal code:  (-6)
[fv-az1442-469:08202] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f09bce42520]
[fv-az1442-469:08202] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f09bce969fc]
[fv-az1442-469:08202] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f09bce42476]
[fv-az1442-469:08202] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f09bce287f3]
[fv-az1442-469:08202] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f09bd2a2b9e]
[fv-az1442-469:08202] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f09bd2ae20c]
[fv-az1442-469:08202] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f09bd2ae277]
[fv-az1442-469:08202] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f09bd2ae52b]
[fv-az1442-469:08202] [ 8] plumed(+0x14254)[0x563ffc38a254]
[fv-az1442-469:08202] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f09bce29d90]
[fv-az1442-469:08202] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f09bce29e40]
[fv-az1442-469:08202] [11] plumed(+0x14eb5)[0x563ffc38aeb5]
[fv-az1442-469:08202] *** End of error message ***
</pre>
{% endraw %}
