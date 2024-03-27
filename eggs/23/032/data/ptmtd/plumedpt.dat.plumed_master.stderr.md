**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: PYTORCH_MODEL_CV LABEL=ptm FILE=plumedpt.pt ATOMS=1,5,13,14,7,10,11,12,15,17,23,24,19,25,27,44,45,29,32,33,42,35,40,37,38,46,48,54,55,50,56,58,71,72,60,63,66,67,68,73,75,95,96,77,80,81,94,83,85,92,86,90,88,97,99,114,115,101,104,106,110,116,118,124,125,120,126,128,136,137,130,133,134,135,138,140,143,144,145,147,150,151,152,162,164,165,159,156,153,166,168,175,176,170,173,177,179,186,187,181,184,188,190,193,194,195,197,217,218,199,202,205,208,210,211,214,219,229,231,232,226,223,220,233,243,245,246,240,237,234,247,257,259,260,254,251,248,261,263,270,271,265,268,272
Maybe a missing space or a typo?
[fv-az1433-905:67822] *** Process received signal ***
[fv-az1433-905:67822] Signal: Aborted (6)
[fv-az1433-905:67822] Signal code:  (-6)
[fv-az1433-905:67822] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f4838042520]
[fv-az1433-905:67822] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f48380969fc]
[fv-az1433-905:67822] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f4838042476]
[fv-az1433-905:67822] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f48380287f3]
[fv-az1433-905:67822] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f48384a4f26]
[fv-az1433-905:67822] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f48384b6d9c]
[fv-az1433-905:67822] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f48384b6e07]
[fv-az1433-905:67822] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f48384b70bb]
[fv-az1433-905:67822] [ 8] plumed_master(+0x12e7f)[0x562ba62dde7f]
[fv-az1433-905:67822] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f4838029d90]
[fv-az1433-905:67822] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f4838029e40]
[fv-az1433-905:67822] [11] plumed_master(+0x13115)[0x562ba62de115]
[fv-az1433-905:67822] *** End of error message ***
</pre>
{% endraw %}
