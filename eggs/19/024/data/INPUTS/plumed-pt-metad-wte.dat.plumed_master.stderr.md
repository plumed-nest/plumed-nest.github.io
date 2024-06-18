**Project ID:** [plumID:19.024]({{ '/' | absolute_url }}eggs/19/024/)  
Stderr for source:  INPUTS/plumed-pt-metad-wte.dat   
Download: [zipped raw stdout](plumed-pt-metad-wte.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-pt-metad-wte.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:547) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled @6.bias in in grid input
[fv-az1435-511:10276] *** Process received signal ***
[fv-az1435-511:10276] Signal: Aborted (6)
[fv-az1435-511:10276] Signal code:  (-6)
[fv-az1435-511:10276] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5cfe042520]
[fv-az1435-511:10276] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5cfe0969fc]
[fv-az1435-511:10276] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5cfe042476]
[fv-az1435-511:10276] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5cfe0287f3]
[fv-az1435-511:10276] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5cfe4a2b9e]
[fv-az1435-511:10276] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5cfe4ae20c]
[fv-az1435-511:10276] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5cfe4ae277]
[fv-az1435-511:10276] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5cfe4ae52b]
[fv-az1435-511:10276] [ 8] plumed_master(+0x14274)[0x55adac919274]
[fv-az1435-511:10276] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5cfe029d90]
[fv-az1435-511:10276] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5cfe029e40]
[fv-az1435-511:10276] [11] plumed_master(+0x14ed5)[0x55adac919ed5]
[fv-az1435-511:10276] *** End of error message ***
</pre>
{% endraw %}
