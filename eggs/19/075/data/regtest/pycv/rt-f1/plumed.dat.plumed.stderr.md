**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervm76f27:10643] *** Process received signal ***
[runnervm76f27:10643] Signal: Aborted (6)
[runnervm76f27:10643] Signal code:  (-6)
[runnervm76f27:10643] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbd7ba45330]
[runnervm76f27:10643] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbd7ba9ec0c]
[runnervm76f27:10643] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbd7ba4527e]
[runnervm76f27:10643] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbd7ba288ff]
[runnervm76f27:10643] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbd7bea5ff5]
[runnervm76f27:10643] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbd7bebb0da]
[runnervm76f27:10643] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbd7bea5a55]
[runnervm76f27:10643] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbd7bea5a6f]
[runnervm76f27:10643] [ 8] plumed(+0x146dd)[0x5557ad3d76dd]
[runnervm76f27:10643] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbd7ba2a1ca]
[runnervm76f27:10643] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbd7ba2a28b]
[runnervm76f27:10643] [11] plumed(+0x15365)[0x5557ad3d8365]
[runnervm76f27:10643] *** End of error message ***
</pre>
{% endraw %}
