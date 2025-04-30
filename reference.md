# Reference
## EligibilityInquiry
<details><summary><code>client.eligibility_inquiry.<a href="src/fernstarterpack/eligibility_inquiry/client.py">medicare_ob_process_main</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
import datetime

from fernstarterpack import Starter
from fernstarterpack.eligibility_inquiry import (
    EligibilityInquiryRequestDetail,
    EligibilityInquiryRequestDetailSubscriber,
    EligibilityInquiryRequestHeader,
)

client = Starter(
    api_key="YOUR_API_KEY",
)
client.eligibility_inquiry.medicare_ob_process_main(
    detail=EligibilityInquiryRequestDetail(
        responsible_reporting_entity="ResponsibleReportingEntity",
        subscriber=EligibilityInquiryRequestDetailSubscriber(
            birthdate=datetime.datetime.fromisoformat(
                "2024-01-15 09:30:00+00:00",
            ),
            first_name="FirstName",
            gender="M",
            last_name="LastName",
            medicare_id_members_medicare_id_hicn_or_mbi="MedicareIDMember’s Medicare ID (HICN or MBI)",
        ),
    ),
    header=EligibilityInquiryRequestHeader(),
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**detail:** `EligibilityInquiryRequestDetail` 
    
</dd>
</dl>

<dl>
<dd>

**header:** `EligibilityInquiryRequestHeader` 
    
</dd>
</dl>

<dl>
<dd>

**meta:** `typing.Optional[EligibilityInquiryRequestMeta]` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## EligibilityResponse
<details><summary><code>client.eligibility_response.<a href="src/fernstarterpack/eligibility_response/client.py">get_document_by_id</a>()</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fernstarterpack import Starter

client = Starter(
    api_key="YOUR_API_KEY",
)
client.eligibility_response.get_document_by_id()

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

