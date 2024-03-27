**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: PAIRENTROPY LABEL=s ATOMS=1-4394 MAXR=2.5 SIGMA=0.05 NLIST NL_CUTOFF=2.8 NL_STRIDE=10
Maybe a missing space or a typo?
[fv-az1433-905:68684] *** Process received signal ***
[fv-az1433-905:68684] Signal: Aborted (6)
[fv-az1433-905:68684] Signal code:  (-6)
[fv-az1433-905:68684] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fdd3d642520]
[fv-az1433-905:68684] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fdd3d6969fc]
[fv-az1433-905:68684] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fdd3d642476]
[fv-az1433-905:68684] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fdd3d6287f3]
[fv-az1433-905:68684] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fdd3daa4f26]
[fv-az1433-905:68684] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fdd3dab6d9c]
[fv-az1433-905:68684] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fdd3dab6e07]
[fv-az1433-905:68684] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fdd3dab70bb]
[fv-az1433-905:68684] [ 8] plumed(+0x12f48)[0x5583a7e8bf48]
[fv-az1433-905:68684] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fdd3d629d90]
[fv-az1433-905:68684] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fdd3d629e40]
[fv-az1433-905:68684] [11] plumed(+0x131e5)[0x5583a7e8c1e5]
[fv-az1433-905:68684] *** End of error message ***
</pre>
{% endraw %}
