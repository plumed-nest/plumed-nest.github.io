**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1215-453:04031] *** Process received signal ***
[fv-az1215-453:04031] Signal: Aborted (6)
[fv-az1215-453:04031] Signal code:  (-6)
[fv-az1215-453:04031] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa553c42520]
[fv-az1215-453:04031] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa553c969fc]
[fv-az1215-453:04031] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa553c42476]
[fv-az1215-453:04031] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa553c287f3]
[fv-az1215-453:04031] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fa5540a2b9e]
[fv-az1215-453:04031] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fa5540ae20c]
[fv-az1215-453:04031] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fa5540ae277]
[fv-az1215-453:04031] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa5540ae52b]
[fv-az1215-453:04031] [ 8] plumed_master(+0x14274)[0x55f25184e274]
[fv-az1215-453:04031] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa553c29d90]
[fv-az1215-453:04031] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa553c29e40]
[fv-az1215-453:04031] [11] plumed_master(+0x14ed5)[0x55f25184eed5]
[fv-az1215-453:04031] *** End of error message ***
</pre>
{% endraw %}
