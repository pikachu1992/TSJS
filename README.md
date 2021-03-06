# TSJS
Truck Simulator Job Searcher (TSJS) is a desktop application that supports more advanced searches compared to the current system used in both Euro Truck Simulator 2 (ETS2) and American Truck Simulator (ATS). TSJS is written in C# using Visual Studio Community 2015 and works by parsing a ``game.sii`` save file which is found in a Windows users ``Documents`` directory, for example ETS2:
``C:\Users\<WINDOWS_UESER_NAME>\Documents\Euro Truck Simulator 2\profiles\<GAME_PROFILE_ID>\save\autosave\game.sii``

Additional profit information is able to be gained from reading game files as this information is not present in save files. However, it is not clear how the game calculates profit during run time and a rough estimate is only provided.

![Screenshot](https://technicism.github.io/images/TSJS/screenshot.png "Screenshot")

## Dependencies
* [SII_Decrypt](https://github.com/ncs-sniper/SII_Decrypt/releases)
* [Game Archive Extractor](http://modding.scssoft.com/wiki/Documentation/Tools/Game_Archive_Extractor#Download)
* ETS2 installed to support ETS2 game save files.
* ATS installed to support ATS game save files.

## License
>THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
