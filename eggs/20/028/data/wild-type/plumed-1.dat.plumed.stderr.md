**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:137) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[fv-az1215-453:09019] *** Process received signal ***
[fv-az1215-453:09019] Signal: Aborted (6)
[fv-az1215-453:09019] Signal code:  (-6)
[fv-az1215-453:09019] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc666842520]
[fv-az1215-453:09019] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc6668969fc]
[fv-az1215-453:09019] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc666842476]
[fv-az1215-453:09019] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc6668287f3]
[fv-az1215-453:09019] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc666ca2b9e]
[fv-az1215-453:09019] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc666cae20c]
[fv-az1215-453:09019] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc666cae277]
[fv-az1215-453:09019] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc666cae52b]
[fv-az1215-453:09019] [ 8] plumed(+0x12f48)[0x55ba70d4af48]
[fv-az1215-453:09019] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc666829d90]
[fv-az1215-453:09019] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc666829e40]
[fv-az1215-453:09019] [11] plumed(+0x131e5)[0x55ba70d4b1e5]
[fv-az1215-453:09019] *** End of error message ***
</pre>
{% endraw %}
