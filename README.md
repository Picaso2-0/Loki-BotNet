# Loki

Loki is a simple **R**emote **A**ccess **T**ool.<br/>
Loki uses **RSA-2048** with **AES-256** to keep your communication with infected machines secure.<br/>

<br/><br/>

<img src="Screenshots/bots.png" atl=""/>

### Disclaimer

```
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

Loki, just like all my other repos is stricly for **educational** purposes.

### Requirements

-   Python **3.6.x** | **3.7.x** | **3.8.x**

### Server tested on

-   Windows 10
-   Kali Linux

### Bot tested on

-   Windows 10

### Payload generator tested on

-   Windows 10

### Features

-   Upload & Download
-   Chrome Launching
-   Persistence
-   Screenshare
-   Screenshot
-   Keylogger
-   SFTP
-   SSH


### Installation

```shell
$> pip install -r requirements.txt
```

### Server side

1. Open `/lib/const.py` & configure your private and public IP's
2. Start loki.py
3. Navigate to http://localhost:5000
4. Login

    ```
    Username: loki
    Password: ikol
    ```

5. Start the server on the same IP as your private IP

### Generate a payload

Navigate to agent directory and run the following command

```shell
$> python builder.py -h
```

**It will not compile inside a virtual environment**

### After connection

-   You can click the id of the bot once it connects

### FYI

-   The bot will call the server using the Public IP, not the private IP
-   The bot will call the server using the port specified on the server tab
