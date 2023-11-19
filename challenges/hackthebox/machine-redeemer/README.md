# Machine: Redeemer

Tag: `Redis Vulnerability Assessment Databases Reconnaissance Anonymous/Guest Access`

## Scanning&#x20;

<figure><img src="../../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

Scanning the network by using nmap tool and we found that target machine running **redis server**&#x20;

<figure><img src="../../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

information and statistics about redis server  t will also display database and keys.

<figure><img src="../../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

**select** database  and list all key by using **keys \*** and **get** key info&#x20;

```
SELECT <database>
keys * 
get key 
```
