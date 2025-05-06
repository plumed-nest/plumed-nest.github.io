**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[fv-az1392-321:64986] *** Process received signal ***
[fv-az1392-321:64986] Signal: Aborted (6)
[fv-az1392-321:64986] Signal code:  (-6)
[fv-az1392-321:64986] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe278e45330]
[fv-az1392-321:64986] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe278e9eb2c]
[fv-az1392-321:64986] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe278e4527e]
[fv-az1392-321:64986] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe278e288ff]
[fv-az1392-321:64986] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe2792a5ff5]
[fv-az1392-321:64986] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe2792bb0da]
[fv-az1392-321:64986] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe2792a5a55]
[fv-az1392-321:64986] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe2792a5a6f]
[fv-az1392-321:64986] [ 8] plumed(+0x146dd)[0x564a39c4b6dd]
[fv-az1392-321:64986] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe278e2a1ca]
[fv-az1392-321:64986] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe278e2a28b]
[fv-az1392-321:64986] [11] plumed(+0x15365)[0x564a39c4c365]
[fv-az1392-321:64986] *** End of error message ***
</pre>
{% endraw %}
