**Jadi Travel**
----
**URL**

  https://travinesia.com:1210/v1/user/register_provider

**Method:**

 `POST`

**Input(Required):**
* **Header**
<br/>
`Authorization : 'Bearer ' + token` <br/>

* **req.body**
<br/>
`travel_name = [String]` <br/>
`slogan = [String]` <br/>
`description = [String]` <br/>
`office_address = [String]` <br/>
`province = [String]` <br/> 
`office_phone_number = [String]` <br/>
`domain = [String]` <br/>
`logo = [String]` <br/>
`medsoc_account = [String]` <br/>
<br />

**URL**

  https://travinesia.com:1210/get/province

**Method:**

 `GET`

**Input(Required):**
* **Header**
<br/>
NONE <br/>

* **req.body**
<br/>
NONE

* **req.params**
<br/>
NONE
<br />

**Profile Travel Agent**
----
**Ubah Profil Travel**
**URL**

  https://travinesia.com:1210/v1/provider/profile

**Method:**

 `GET`

**Input(Required):**
* **Header**
<br/>
`Authorization : 'Bearer ' + token` <br/>

* **req.body**
<br/>
NONE

* **req.params**
<br/>
NONE
<br />

**URL**

  https://travinesia.com:1210/get/province

**Method:**

 `GET`

**Input(Required):**
* **Header**
<br/>
NONE <br/>

* **req.body**
<br/>
NONE

* **req.params**
<br/>
NONE
<br />

**URL**

  https://travinesia.com:1210/v1/provider/profile

**Method:**

 `PUT`

**Input(Required):**
* **Header**
<br/>
`Authorization : 'Bearer ' + token` <br/>

* **req.body**
<br/>
`slogan = [String]` <br />
`description = [String]` <br />
`office_address = [String]` <br />
`province = [String]` <br /> 
`office_phone_number = [String]` <br />

* **req.params**
<br/>
NONE
<br />

**Ubah Cover Travel**
**URL**

  https://travinesia.com:1210/v1/provider/edit_cover

**Method:**

 `PUT`

**Input(Required):**
* **Header**
<br/>
`Authorization : 'Bearer ' + token` <br/>

* **req.body**
<br/>
`cover = [String]` <br /> 

* **req.params**
<br/>
NONE
<br />

**Ubah logo Travel**
**URL**

  https://travinesia.com:1210/v1/provider/edit_logo

**Method:**

 `PUT`

**Input(Required):**
* **Header**
<br/>
`Authorization : 'Bearer ' + token` <br/>

* **req.body**
<br/>
`logo = [String]` <br /> 

* **req.params**
<br/>
NONE
<br />








