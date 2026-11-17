# Reference
## BillingNotes
<details><summary><code>client.billingNotes.<a href="/src/api/resources/billingNotes/client/Client.ts">create</a>({ ...params }) -> Taiga.BillingNotesv2BillingNote</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.billingNotes.create({
    text: "text",
    encounter_id: "encounter_id"
});

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

**request:** `Taiga.CreateBillingNotesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BillingNotesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.billingNotes.<a href="/src/api/resources/billingNotes/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.billingNotes.delete({
    billing_note_id: "billing_note_id"
});

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

**request:** `Taiga.DeleteBillingNotesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BillingNotesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.billingNotes.<a href="/src/api/resources/billingNotes/client/Client.ts">update</a>({ ...params }) -> Taiga.BillingNotesv2BillingNote</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.billingNotes.update({
    billing_note_id: "billing_note_id",
    text: "text"
});

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

**request:** `Taiga.UpdateBillingNotesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BillingNotesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## ChargeCaptureBundles
<details><summary><code>client.chargeCaptureBundles.<a href="/src/api/resources/chargeCaptureBundles/client/Client.ts">get</a>({ ...params }) -> Taiga.ChargeCaptureBundlesv1ChargeCaptureClaimCreation</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.chargeCaptureBundles.get({
    charge_capture_claim_creation_id: "charge_capture_claim_creation_id"
});

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

**request:** `Taiga.GetChargeCaptureBundlesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ChargeCaptureBundlesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.chargeCaptureBundles.<a href="/src/api/resources/chargeCaptureBundles/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.ChargeCaptureBundlesv1ChargeCaptureClaimCreation, Taiga.ChargeCaptureBundlesv1ChargeCaptureClaimCreationPage&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.chargeCaptureBundles.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.chargeCaptureBundles.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListChargeCaptureBundlesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ChargeCaptureBundlesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## ChargeCapture
<details><summary><code>client.chargeCapture.<a href="/src/api/resources/chargeCapture/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.ChargeCapturev1ChargeCapture, Taiga.ChargeCapturev1ChargeCapturePage&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.chargeCapture.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.chargeCapture.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListChargeCaptureRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ChargeCaptureClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.chargeCapture.<a href="/src/api/resources/chargeCapture/client/Client.ts">create</a>({ ...params }) -> Taiga.ChargeCapturev1ChargeCapture</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.chargeCapture.create({
    data: {},
    charge_external_id: "charge_external_id",
    patient_external_id: "patient_external_id",
    status: "planned"
});

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

**request:** `Taiga.CreateChargeCaptureRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ChargeCaptureClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.chargeCapture.<a href="/src/api/resources/chargeCapture/client/Client.ts">createFromPreEncounterPatient</a>({ ...params }) -> Taiga.ChargeCapturev1ChargeCapture</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a Charge Capture from a pre-encounter patient and appointment. This endpoint is intended to be used by consumers who are managing
patients and appointments in the pre-encounter service and is currently under development. Consumers who are not taking advantage
of the pre-encounter service should use the standard create endpoint.

At encounter creation time, information from the provided patient and appointment objects will be populated
where applicable. In particular, the following fields are populated from the patient and appointment objects:
  - Patient
  - Referring Provider
  - Subscriber Primary
  - Subscriber Secondary
  - Referral Number
  - Responsible Party
  - Guarantor

Note that these fields should not be populated in the ChargeCaptureData property of this endpoint, as they will be overwritten at encounter creation time.

Utilizing this endpoint opts you into automatic updating of the encounter when the patient or appointment is updated, assuming the
encounter has not already been submitted or adjudicated.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.chargeCapture.createFromPreEncounterPatient({
    data: {},
    charge_external_id: "charge_external_id",
    pre_encounter_patient_id: "pre_encounter_patient_id",
    pre_encounter_appointment_ids: ["pre_encounter_appointment_ids"],
    status: "planned"
});

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

**request:** `Taiga.CreateFromPreEncounterPatientChargeCaptureRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ChargeCaptureClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.chargeCapture.<a href="/src/api/resources/chargeCapture/client/Client.ts">get</a>({ ...params }) -> Taiga.ChargeCapturev1ChargeCapture</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.chargeCapture.get({
    charge_capture_id: "charge_capture_id"
});

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

**request:** `Taiga.GetChargeCaptureRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ChargeCaptureClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.chargeCapture.<a href="/src/api/resources/chargeCapture/client/Client.ts">update</a>({ ...params }) -> Taiga.ChargeCapturev1ChargeCapture</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.chargeCapture.update({
    charge_capture_id: "charge_capture_id"
});

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

**request:** `Taiga.UpdateChargeCaptureRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ChargeCaptureClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Contracts
<details><summary><code>client.contracts.<a href="/src/api/resources/contracts/client/Client.ts">get</a>({ ...params }) -> Taiga.Contractsv3ContractWithProvidersUnion</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contracts.get({
    contract_id: "contract_id"
});

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

**request:** `Taiga.GetContractsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contracts.<a href="/src/api/resources/contracts/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contracts.delete({
    contract_id: "contract_id"
});

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

**request:** `Taiga.DeleteContractsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contracts.<a href="/src/api/resources/contracts/client/Client.ts">update</a>({ ...params }) -> Taiga.Contractsv3ContractWithProvidersUnion</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contracts.update({
    contract_id: "contract_id",
    body: {
        type: "professional"
    }
});

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

**request:** `Taiga.UpdateContractsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contracts.<a href="/src/api/resources/contracts/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.Contractsv3ContractUnion, Taiga.Contractsv3ContractsPage&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.contracts.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.contracts.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListContractsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contracts.<a href="/src/api/resources/contracts/client/Client.ts">create</a>({ ...params }) -> Taiga.Contractsv3ContractWithProvidersUnion</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates a new contract within the user's current organization
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contracts.create({
    effective_date: "effective_date",
    regions: {
        states: ["AA"],
        type: "states"
    },
    commercial_insurance_types: {
        type: "allApply"
    },
    medicare_insurance_types: {
        type: "allApply"
    },
    medicaid_insurance_types: {
        type: "allApply"
    },
    contract_type: "professional",
    contracting_provider_id: "contracting_provider_id",
    payer_uuid: "payer_uuid",
    rendering_provider_ids: ["rendering_provider_ids"],
    type: "professional"
});

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

**request:** `Taiga.Contractsv3ContractCreateUnion` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contracts.<a href="/src/api/resources/contracts/client/Client.ts">getProviders</a>({ ...params }) -> core.Page&lt;Taiga.OrganizationProvidersv2OrganizationProvider, Taiga.Contractsv3ContractProvidersPage&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.contracts.getProviders({
    contract_id: "contract_id"
});
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.contracts.getProviders({
    contract_id: "contract_id"
});
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.GetProvidersContractsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contracts.<a href="/src/api/resources/contracts/client/Client.ts">addProviders</a>({ ...params }) -> Taiga.Contractsv3AddContractProvidersResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Appends a list of rendering provider IDs to the contract. Provider IDs already on the contract are silently ignored.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contracts.addProviders({
    contract_id: "contract_id",
    rendering_provider_ids: ["rendering_provider_ids"]
});

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

**request:** `Taiga.AddProvidersContractsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contracts.<a href="/src/api/resources/contracts/client/Client.ts">removeProviders</a>({ ...params }) -> Taiga.Contractsv3ContractProviderCount</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Removes the specified rendering provider IDs from the contract. Returns a 404 if any of the provided IDs are not currently in the contract.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contracts.removeProviders({
    contract_id: "contract_id",
    rendering_provider_ids: ["rendering_provider_ids"]
});

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

**request:** `Taiga.RemoveProvidersContractsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contracts.<a href="/src/api/resources/contracts/client/Client.ts">getProviderCredentialingSpans</a>({ ...params }) -> core.Page&lt;Taiga.Contractsv3ContractProviderCredentialing, Taiga.Contractsv3ContractProviderCredentialingPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns rendering providers linked to a contract with their credentialing spans, scoped to the contract's contracting provider and payer. Providers with no matching spans are included with an empty list.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.contracts.getProviderCredentialingSpans({
    contract_id: "contract_id"
});
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.contracts.getProviderCredentialingSpans({
    contract_id: "contract_id"
});
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.GetProviderCredentialingSpansContractsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contracts.<a href="/src/api/resources/contracts/client/Client.ts">createServiceFacility</a>({ ...params }) -> Taiga.Contractsv3ContractServiceFacility</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contracts.createServiceFacility({
    contract_id: "contract_id",
    body: {
        service_facility_id: "service_facility_id",
        provider_ids: ["provider_ids"]
    }
});

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

**request:** `Taiga.CreateServiceFacilityContractsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contracts.<a href="/src/api/resources/contracts/client/Client.ts">updateServiceFacility</a>({ ...params }) -> Taiga.Contractsv3ContractServiceFacility</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contracts.updateServiceFacility({
    contract_id: "contract_id",
    contract_service_facility_id: "contract_service_facility_id"
});

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

**request:** `Taiga.UpdateServiceFacilityContractsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Credentialing
<details><summary><code>client.credentialing.<a href="/src/api/resources/credentialing/client/Client.ts">listFacilities</a>({ ...params }) -> core.Page&lt;Taiga.Credentialingv2FacilityCredentialingSpan, Taiga.Credentialingv2FacilityCredentialingSpanPage&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.credentialing.listFacilities();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.credentialing.listFacilities();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListFacilitiesCredentialingRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CredentialingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.credentialing.<a href="/src/api/resources/credentialing/client/Client.ts">createFacility</a>({ ...params }) -> Taiga.Credentialingv2FacilityCredentialingSpan</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.credentialing.createFacility({
    service_facility_id: "service_facility_id",
    contracting_provider_id: "contracting_provider_id",
    payer_uuid: "payer_uuid"
});

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

**request:** `Taiga.CreateFacilityCredentialingRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CredentialingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.credentialing.<a href="/src/api/resources/credentialing/client/Client.ts">getFacility</a>({ ...params }) -> Taiga.Credentialingv2FacilityCredentialingSpan</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.credentialing.getFacility({
    facility_credentialing_id: "facility_credentialing_id"
});

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

**request:** `Taiga.GetFacilityCredentialingRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CredentialingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.credentialing.<a href="/src/api/resources/credentialing/client/Client.ts">deleteFacility</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Soft deletes a credentialing span rate from the system.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.credentialing.deleteFacility({
    facility_credentialing_id: "facility_credentialing_id"
});

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

**request:** `Taiga.DeleteFacilityCredentialingRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CredentialingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.credentialing.<a href="/src/api/resources/credentialing/client/Client.ts">updateFacility</a>({ ...params }) -> Taiga.Credentialingv2FacilityCredentialingSpan</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.credentialing.updateFacility({
    facility_credentialing_id: "facility_credentialing_id",
    contracting_provider_id: "contracting_provider_id"
});

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

**request:** `Taiga.UpdateFacilityCredentialingRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CredentialingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.credentialing.<a href="/src/api/resources/credentialing/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.Credentialingv2ProviderCredentialingSpan, Taiga.Credentialingv2ProviderCredentialingSpanPage&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.credentialing.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.credentialing.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListCredentialingRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CredentialingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.credentialing.<a href="/src/api/resources/credentialing/client/Client.ts">create</a>({ ...params }) -> Taiga.Credentialingv2ProviderCredentialingSpan</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.credentialing.create({
    rendering_provider_id: "rendering_provider_id",
    contracting_provider_id: "contracting_provider_id",
    payer_uuid: "payer_uuid",
    regions: {
        states: ["AA"],
        type: "states"
    }
});

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

**request:** `Taiga.CreateCredentialingRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CredentialingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.credentialing.<a href="/src/api/resources/credentialing/client/Client.ts">get</a>({ ...params }) -> Taiga.Credentialingv2ProviderCredentialingSpan</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.credentialing.get({
    provider_credentialing_id: "provider_credentialing_id"
});

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

**request:** `Taiga.GetCredentialingRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CredentialingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.credentialing.<a href="/src/api/resources/credentialing/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Soft deletes a credentialing span rate from the system.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.credentialing.delete({
    provider_credentialing_id: "provider_credentialing_id"
});

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

**request:** `Taiga.DeleteCredentialingRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CredentialingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.credentialing.<a href="/src/api/resources/credentialing/client/Client.ts">update</a>({ ...params }) -> Taiga.Credentialingv2ProviderCredentialingSpan</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.credentialing.update({
    provider_credentialing_id: "provider_credentialing_id"
});

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

**request:** `Taiga.UpdateCredentialingRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CredentialingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## EncounterAttachments
<details><summary><code>client.encounterAttachments.<a href="/src/api/resources/encounterAttachments/client/Client.ts">get</a>({ ...params }) -> Taiga.EncounterAttachmentsv1EncounterAttachment[]</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterAttachments.get({
    encounter_id: "encounter_id"
});

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

**request:** `Taiga.GetEncounterAttachmentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterAttachmentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterAttachments.<a href="/src/api/resources/encounterAttachments/client/Client.ts">create</a>({ ...params }) -> Taiga.EncounterAttachmentsv1AttachmentId</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Uploads a file to the encounter. The file will be stored in the
encounter's attachments. Deprecated: Use create-v2 instead.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterAttachments.create({
    encounter_id: "encounter_id"
});

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

**request:** `Taiga.CreateEncounterAttachmentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterAttachmentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterAttachments.<a href="/src/api/resources/encounterAttachments/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterAttachments.delete({
    encounter_id: "encounter_id",
    attachment_id: "attachment_id"
});

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

**request:** `Taiga.DeleteEncounterAttachmentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterAttachmentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterAttachments.<a href="/src/api/resources/encounterAttachments/client/Client.ts">createWithDescription</a>({ ...params }) -> Taiga.EncounterAttachmentsv1AttachmentId</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Uploads a file to the encounter. The file will be stored in the
encounter's attachments.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterAttachments.createWithDescription({
    encounter_id: "encounter_id"
});

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

**request:** `Taiga.CreateWithDescriptionEncounterAttachmentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterAttachmentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## EncounterProviders
<details><summary><code>client.encounterProviders.<a href="/src/api/resources/encounterProviders/client/Client.ts">updateReferringProvider</a>({ ...params }) -> Taiga.EncounterProvidersv2EncounterProvider</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterProviders.updateReferringProvider({
    encounter_id: "encounter_id",
    body: {}
});

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

**request:** `Taiga.UpdateReferringProviderEncounterProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterProviders.<a href="/src/api/resources/encounterProviders/client/Client.ts">deleteInitialReferringProvider</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterProviders.deleteInitialReferringProvider({
    encounter_id: "encounter_id"
});

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

**request:** `Taiga.DeleteInitialReferringProviderEncounterProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterProviders.<a href="/src/api/resources/encounterProviders/client/Client.ts">updateInitialReferringProvider</a>({ ...params }) -> Taiga.EncounterProvidersv2EncounterProvider</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterProviders.updateInitialReferringProvider({
    encounter_id: "encounter_id",
    body: {}
});

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

**request:** `Taiga.UpdateInitialReferringProviderEncounterProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterProviders.<a href="/src/api/resources/encounterProviders/client/Client.ts">deleteSupervisingProvider</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterProviders.deleteSupervisingProvider({
    encounter_id: "encounter_id"
});

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

**request:** `Taiga.DeleteSupervisingProviderEncounterProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterProviders.<a href="/src/api/resources/encounterProviders/client/Client.ts">updateSupervisingProvider</a>({ ...params }) -> Taiga.EncounterProvidersv2EncounterProvider</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterProviders.updateSupervisingProvider({
    encounter_id: "encounter_id",
    body: {}
});

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

**request:** `Taiga.UpdateSupervisingProviderEncounterProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterProviders.<a href="/src/api/resources/encounterProviders/client/Client.ts">deleteOrderingProvider</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterProviders.deleteOrderingProvider({
    service_line_id: "service_line_id"
});

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

**request:** `Taiga.DeleteOrderingProviderEncounterProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterProviders.<a href="/src/api/resources/encounterProviders/client/Client.ts">updateOrderingProvider</a>({ ...params }) -> Taiga.EncounterProvidersv2EncounterProvider</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterProviders.updateOrderingProvider({
    service_line_id: "service_line_id"
});

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

**request:** `Taiga.EncounterProvidersv2OrderingProviderUpdate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterProviders.<a href="/src/api/resources/encounterProviders/client/Client.ts">createReferringProvider</a>({ ...params }) -> Taiga.EncounterProvidersv2EncounterProvider</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterProviders.createReferringProvider({
    encounter_id: "encounter_id",
    body: {
        npi: "npi"
    }
});

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

**request:** `Taiga.CreateReferringProviderEncounterProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterProviders.<a href="/src/api/resources/encounterProviders/client/Client.ts">createInitialReferringProvider</a>({ ...params }) -> Taiga.EncounterProvidersv2EncounterProvider</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterProviders.createInitialReferringProvider({
    encounter_id: "encounter_id",
    body: {
        npi: "npi"
    }
});

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

**request:** `Taiga.CreateInitialReferringProviderEncounterProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterProviders.<a href="/src/api/resources/encounterProviders/client/Client.ts">createSupervisingProvider</a>({ ...params }) -> Taiga.EncounterProvidersv2EncounterProvider</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterProviders.createSupervisingProvider({
    encounter_id: "encounter_id",
    body: {
        npi: "npi"
    }
});

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

**request:** `Taiga.CreateSupervisingProviderEncounterProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterProviders.<a href="/src/api/resources/encounterProviders/client/Client.ts">createOrderingProvider</a>({ ...params }) -> Taiga.EncounterProvidersv2EncounterProvider</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterProviders.createOrderingProvider({
    service_line_id: "service_line_id",
    body: {
        npi: "npi"
    }
});

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

**request:** `Taiga.CreateOrderingProviderEncounterProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterProviders.<a href="/src/api/resources/encounterProviders/client/Client.ts">deleteReferringProvider</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterProviders.deleteReferringProvider({
    encounter_id: "encounter_id"
});

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

**request:** `Taiga.DeleteReferringProviderEncounterProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## EncounterSupplementalInformation
<details><summary><code>client.encounterSupplementalInformation.<a href="/src/api/resources/encounterSupplementalInformation/client/Client.ts">get</a>({ ...params }) -> Taiga.EncounterSupplementalInformationv1SupplementalInformation[]</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterSupplementalInformation.get({
    encounter_id: "encounter_id"
});

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

**request:** `Taiga.GetEncounterSupplementalInformationRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterSupplementalInformationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterSupplementalInformation.<a href="/src/api/resources/encounterSupplementalInformation/client/Client.ts">create</a>({ ...params }) -> Taiga.EncounterSupplementalInformationv1SupplementalInformation</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterSupplementalInformation.create({
    encounter_id: "encounter_id",
    attachment_report_type_code: "03",
    attachment_transmission_code: "AA",
    attachment_inclusion: "not_included"
});

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

**request:** `Taiga.EncounterSupplementalInformationv1CreateSupplementalInformationRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterSupplementalInformationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterSupplementalInformation.<a href="/src/api/resources/encounterSupplementalInformation/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterSupplementalInformation.delete({
    encounter_id: "encounter_id",
    supplemental_information_id: "supplemental_information_id"
});

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

**request:** `Taiga.DeleteEncounterSupplementalInformationRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterSupplementalInformationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounterSupplementalInformation.<a href="/src/api/resources/encounterSupplementalInformation/client/Client.ts">update</a>({ ...params }) -> Taiga.EncounterSupplementalInformationv1SupplementalInformation</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounterSupplementalInformation.update({
    encounter_id: "encounter_id",
    supplemental_information_id: "supplemental_information_id"
});

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

**request:** `Taiga.EncounterSupplementalInformationv1UpdateSupplementalInformationRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncounterSupplementalInformationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Encounters
<details><summary><code>client.encounters.<a href="/src/api/resources/encounters/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.Encountersv4Encounter, Taiga.Encountersv4EncounterPage&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.encounters.list({
    date_of_service_min: "2019-08-24",
    date_of_service_max: "2019-08-25",
    primary_payer_names: "Medicare,Medicaid",
    search_term: "doe",
    diagnoses_updated_since: "2019-08-24T14:15:22Z"
});
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.encounters.list({
    date_of_service_min: "2019-08-24",
    date_of_service_max: "2019-08-25",
    primary_payer_names: "Medicare,Medicaid",
    search_term: "doe",
    diagnoses_updated_since: "2019-08-24T14:15:22Z"
});
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListEncountersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncountersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounters.<a href="/src/api/resources/encounters/client/Client.ts">create</a>({ ...params }) -> Taiga.Encountersv4Encounter</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounters.create({
    external_id: "external_id",
    patient_authorized_release: true,
    benefits_assigned_to_provider: true,
    provider_accepts_assignment: true,
    billable_status: "BILLABLE",
    patient: {
        first_name: "first_name",
        last_name: "last_name",
        gender: "male",
        external_id: "external_id",
        date_of_birth: "2023-01-15",
        address: {
            address1: "address1",
            city: "city",
            state: "AA",
            zip_code: "zip_code"
        }
    },
    responsible_party: "INSURANCE_PAY",
    billing_provider: {
        address: {
            address1: "address1",
            city: "city",
            state: "AA",
            zip_code: "zip_code",
            zip_plus_four_code: "1234"
        },
        tax_id: "tax_id",
        npi: "npi"
    },
    diagnoses: [{
            code_type: "ABF",
            code: "code"
        }],
    place_of_service_code: "01",
    rendering_provider: {
        npi: "npi"
    }
});

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

**request:** `Taiga.Encountersv4EncounterCreate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncountersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounters.<a href="/src/api/resources/encounters/client/Client.ts">get</a>({ ...params }) -> Taiga.Encountersv4Encounter</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounters.get({
    encounter_id: "encounter_id"
});

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

**request:** `Taiga.GetEncountersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncountersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounters.<a href="/src/api/resources/encounters/client/Client.ts">update</a>({ ...params }) -> Taiga.Encountersv4Encounter</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounters.update({
    encounter_id: "encounter_id"
});

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

**request:** `Taiga.Encountersv4EncounterUpdate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncountersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounters.<a href="/src/api/resources/encounters/client/Client.ts">createUniversal</a>({ ...params }) -> Taiga.Encountersv4Encounter</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Notice: The UB-04 Data File, 2025, is copyrighted by American Hospital Association (AHA), Chicago, Illinois.
No portion of the THE UB-04 Data File, may be reproduced, stored in a retrieval system, or transmitted,
in any form or by any means, electronic, mechanical, photocopying, recording, or otherwise, without prior
express, written consent of AHA.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounters.createUniversal({
    external_id: "external_id",
    patient_authorized_release: true,
    benefits_assigned_to_provider: true,
    provider_accepts_assignment: true,
    billable_status: "BILLABLE",
    patient: {
        first_name: "first_name",
        last_name: "last_name",
        gender: "male",
        external_id: "external_id",
        date_of_birth: "2023-01-15",
        address: {
            address1: "address1",
            city: "city",
            state: "AA",
            zip_code: "zip_code"
        }
    },
    responsible_party: "INSURANCE_PAY",
    billing_provider: {
        address: {
            address1: "address1",
            city: "city",
            state: "AA",
            zip_code: "zip_code",
            zip_plus_four_code: "1234"
        },
        tax_id: "tax_id",
        npi: "npi"
    },
    submission_expectation: "TARGET_PROFESSIONAL"
});

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

**request:** `Taiga.EncountersUniversalUniversalEncounterCreate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncountersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounters.<a href="/src/api/resources/encounters/client/Client.ts">createFromPreEncounterPatientUniversal</a>({ ...params }) -> Taiga.Encountersv4Encounter</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create an encounter from a pre-encounter patient and appointment. This endpoint is intended to be used by consumers who are managing
patients and appointments in the pre-encounter service and is currently under development. Consumers who are not taking advantage
of the pre-encounter service should use the standard create endpoint.

The endpoint will create an encounter from the provided fields, pulling information from the provided patient and appointment objects
where applicable. In particular, the following fields are populated from the patient and appointment objects:
  - Patient
  - Referring Provider
  - Subscriber Primary
  - Subscriber Secondary
  - Referral Number
  - Responsible Party
  - Guarantor

Utilizing this endpoint opts you into automatic updating of the encounter when the patient or appointment is updated, assuming the
encounter has not already been submitted or adjudicated.

Notice: The UB-04 Data File, 2025, is copyrighted by American Hospital Association (AHA), Chicago, Illinois.
No portion of the THE UB-04 Data File, may be reproduced, stored in a retrieval system, or transmitted,
in any form or by any means, electronic, mechanical, photocopying, recording, or otherwise, without prior
express, written consent of AHA.

A saved primary coverage with payer_id VBA (Taiga's manual routing identifier for Vision Benefits of America) routes to manual submission. Empty diagnoses and diagnosis pointers are allowed on this manual path. A 202 response is a manual receipt, not an encounter or a payer acknowledgment. All other payer IDs retain normal electronic processing; unknown payers are not automatically routed to manual review.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounters.createFromPreEncounterPatientUniversal({
    external_id: "external_id",
    patient_authorized_release: true,
    benefits_assigned_to_provider: true,
    provider_accepts_assignment: true,
    billable_status: "BILLABLE",
    pre_encounter_patient_id: "pre_encounter_patient_id",
    pre_encounter_appointment_ids: ["pre_encounter_appointment_ids"],
    billing_provider: {
        address: {
            address1: "address1",
            city: "city",
            state: "AA",
            zip_code: "zip_code",
            zip_plus_four_code: "1234"
        },
        tax_id: "tax_id",
        npi: "npi"
    },
    submission_expectation: "TARGET_PROFESSIONAL"
});

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

**request:** `Taiga.EncountersUniversalUniversalEncounterCreateFromPreEncounter` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncountersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounters.<a href="/src/api/resources/encounters/client/Client.ts">createFromPreEncounterPatient</a>({ ...params }) -> Taiga.Encountersv4Encounter</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create an encounter from a pre-encounter patient and appointment. This endpoint is intended to be used by consumers who are managing
patients and appointments in the pre-encounter service and is currently under development. Consumers who are not taking advantage
of the pre-encounter service should use the standard create endpoint.

The endpoint will create an encounter from the provided fields, pulling information from the provided patient and appointment objects
where applicable. In particular, the following fields are populated from the patient and appointment objects:
  - Patient
  - Referring Provider
  - Subscriber Primary
  - Subscriber Secondary
  - Referral Number
  - Responsible Party
  - Guarantor

Utilizing this endpoint opts you into automatic updating of the encounter when the patient or appointment is updated, assuming the
encounter has not already been submitted or adjudicated.

A saved primary coverage with payer_id VBA (Taiga's manual routing identifier for Vision Benefits of America) routes to manual submission. Empty diagnoses and diagnosis pointers are allowed on this manual path. A 202 response is a manual receipt, not an encounter or a payer acknowledgment. All other payer IDs retain normal electronic processing; unknown payers are not automatically routed to manual review.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounters.createFromPreEncounterPatient({
    external_id: "external_id",
    patient_authorized_release: true,
    benefits_assigned_to_provider: true,
    provider_accepts_assignment: true,
    billable_status: "BILLABLE",
    pre_encounter_patient_id: "pre_encounter_patient_id",
    pre_encounter_appointment_ids: ["pre_encounter_appointment_ids"],
    billing_provider: {
        address: {
            address1: "address1",
            city: "city",
            state: "AA",
            zip_code: "zip_code",
            zip_plus_four_code: "1234"
        },
        tax_id: "tax_id",
        npi: "npi"
    },
    rendering_provider: {
        npi: "npi"
    },
    place_of_service_code: "01",
    diagnoses: [{
            code_type: "ABF",
            code: "code"
        }]
});

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

**request:** `Taiga.Encountersv4EncounterCreateFromPreEncounter` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncountersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.encounters.<a href="/src/api/resources/encounters/client/Client.ts">updateUniversal</a>({ ...params }) -> Taiga.Encountersv4Encounter</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Notice: The UB-04 Data File, 2025, is copyrighted by American Hospital Association (AHA), Chicago, Illinois.
No portion of the THE UB-04 Data File, may be reproduced, stored in a retrieval system, or transmitted,
in any form or by any means, electronic, mechanical, photocopying, recording, or otherwise, without prior
express, written consent of AHA.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.encounters.updateUniversal({
    encounter_id: "encounter_id"
});

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

**request:** `Taiga.EncountersUniversalUniversalEncounterUpdate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EncountersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## FeeSchedules
<details><summary><code>client.feeSchedules.<a href="/src/api/resources/feeSchedules/client/Client.ts">getMatch</a>({ ...params }) -> Taiga.FeeSchedulesv3MatchResult</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets the rate that matches a service line.  No result means no rate exists matching the service line's dimensions.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.feeSchedules.getMatch({
    service_line_id: "service_line_id"
});

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

**request:** `Taiga.GetMatchFeeSchedulesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FeeSchedulesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.feeSchedules.<a href="/src/api/resources/feeSchedules/client/Client.ts">testMatch</a>({ ...params }) -> Taiga.FeeSchedulesv3MatchTestResult</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Tests a service line against a rate to see if it matches.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.feeSchedules.testMatch({
    service_line_id: "service_line_id",
    rate_id: "rate_id"
});

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

**request:** `Taiga.TestMatchFeeSchedulesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FeeSchedulesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.feeSchedules.<a href="/src/api/resources/feeSchedules/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.FeeSchedulesv3Rate, Taiga.FeeSchedulesv3RatesPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets a list of dimensions with their rates. The rates returned will always be the most recent versions of those rates.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.feeSchedules.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.feeSchedules.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListFeeSchedulesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FeeSchedulesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.feeSchedules.<a href="/src/api/resources/feeSchedules/client/Client.ts">upload</a>({ ...params }) -> Taiga.FeeSchedulesv3Rate[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Uploads a new fee schedule.

Each rate may either be totally new as qualified by its dimensions or a new version for an existing rate.

If adding a new version to an existing rate, the rate must be posted with the next version number (previous version + 1) or a EntityConflictError will
be returned.

Use the dry run flag to discover already existing rates and to run validations.  If validations for any rate fail, no rates will
be saved to the system.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.feeSchedules.upload({
    dry_run: true,
    rates: [{
            dimensions: {
                payer_uuid: "payer_uuid",
                organization_billing_provider_id: "organization_billing_provider_id",
                states: ["AA"],
                zip_codes: ["zip_codes"],
                license_types: ["MD"],
                facility_type_codes: ["01"],
                network_types: ["12"],
                payer_plan_group_ids: ["payer_plan_group_ids"],
                cpt_code: "cpt_code",
                modifiers: ["AV"]
            },
            entries: [{
                    start_date: "2024-04-11",
                    rate_cents: 33000,
                    is_deactivated: false
                }],
            type: "new_rate"
        }]
});

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

**request:** `Taiga.UploadFeeSchedulesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FeeSchedulesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.feeSchedules.<a href="/src/api/resources/feeSchedules/client/Client.ts">getUniqueValuesForDimension</a>({ ...params }) -> core.Page&lt;Taiga.FeeSchedulesv3OptionalDimensions, Taiga.FeeSchedulesv3DimensionsPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets unique values for a dimension based on other selection criteria. The response is a list of dimensions with your criteria and the unique values populated. This API is useful for driving pivots on dimension values.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.feeSchedules.getUniqueValuesForDimension({
    pivot_dimension: "payer_uuid"
});
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.feeSchedules.getUniqueValuesForDimension({
    pivot_dimension: "payer_uuid"
});
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.GetUniqueValuesForDimensionFeeSchedulesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FeeSchedulesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.feeSchedules.<a href="/src/api/resources/feeSchedules/client/Client.ts">getRateHistory</a>({ ...params }) -> Taiga.FeeSchedulesv3Rate[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets every version of a rate.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.feeSchedules.getRateHistory({
    rate_id: "rate_id"
});

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

**request:** `Taiga.GetRateHistoryFeeSchedulesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FeeSchedulesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.feeSchedules.<a href="/src/api/resources/feeSchedules/client/Client.ts">deleteRate</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Soft deletes a rate from the system.  Only the most recent version of a rate can be deleted.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.feeSchedules.deleteRate({
    rate_id: "rate_id",
    version: 1
});

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

**request:** `Taiga.DeleteRateFeeSchedulesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FeeSchedulesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.feeSchedules.<a href="/src/api/resources/feeSchedules/client/Client.ts">getPayerThresholdsDefault</a>() -> Taiga.FeeSchedulesv3PayerThreshold</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets the default payer threshold
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.feeSchedules.getPayerThresholdsDefault();

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

**requestOptions:** `FeeSchedulesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.feeSchedules.<a href="/src/api/resources/feeSchedules/client/Client.ts">getPayerThresholds</a>({ ...params }) -> Taiga.FeeSchedulesv3PayerThresholdsPage</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets a list of payers and thresholds by their uuids
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.feeSchedules.getPayerThresholds({
    payer_uuids: ["payer_uuids"]
});

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

**request:** `Taiga.GetPayerThresholdsFeeSchedulesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FeeSchedulesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.feeSchedules.<a href="/src/api/resources/feeSchedules/client/Client.ts">setPayerThreshold</a>({ ...params }) -> Taiga.FeeSchedulesv3PayerThreshold</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sets the threshold information for a payer
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.feeSchedules.setPayerThreshold({
    payer_uuid: "payer_uuid",
    body: {
        disable_paid_incorrectly: true
    }
});

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

**request:** `Taiga.SetPayerThresholdFeeSchedulesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FeeSchedulesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.feeSchedules.<a href="/src/api/resources/feeSchedules/client/Client.ts">hardDeleteRates</a>({ ...params }) -> number</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Hard deletes rates from the system that match the provided dimensions.  This is a destructive operation and cannot be undone.  If an empty dimensions object is provided, all rates will be hard deleted.  The maximum number of rates this API will delete at a time is 10000.  Returns the number of rates deleted and if that number is the maximum, the caller should call this API again to continue deleting rates.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.feeSchedules.hardDeleteRates({
    states: ["AA"],
    zip_codes: ["zip_codes"],
    license_types: ["MD"],
    facility_type_codes: ["01"],
    network_types: ["12"],
    payer_plan_group_ids: ["payer_plan_group_ids"],
    modifiers: ["AV"]
});

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

**request:** `Taiga.FeeSchedulesv3OptionalDimensions` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FeeSchedulesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.feeSchedules.<a href="/src/api/resources/feeSchedules/client/Client.ts">hardDeleteRatesByIds</a>({ ...params }) -> number</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Hard deletes specific rates from the system by their IDs. This is a destructive operation and cannot be undone. Limited to 100 rate IDs maximum per request. For bulk deletion of more than 100 rates, use the hard_delete_rates endpoint with dimension filters. Returns the number of rates deleted.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.feeSchedules.hardDeleteRatesByIds({
    rate_ids: ["rate_ids"]
});

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

**request:** `Taiga.HardDeleteRatesByIdsFeeSchedulesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FeeSchedulesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Guarantor
<details><summary><code>client.guarantor.<a href="/src/api/resources/guarantor/client/Client.ts">create</a>({ ...params }) -> Taiga.Guarantorv1Guarantor</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates a new guarantor and returns the newly created Guarantor object.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.guarantor.create({
    encounter_id: "encounter_id",
    body: {
        first_name: "first_name",
        last_name: "last_name",
        external_id: "external_id",
        address: {
            address1: "address1",
            city: "city",
            state: "AA",
            zip_code: "zip_code"
        }
    }
});

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

**request:** `Taiga.CreateGuarantorRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GuarantorClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.guarantor.<a href="/src/api/resources/guarantor/client/Client.ts">get</a>({ ...params }) -> Taiga.Guarantorv1Guarantor</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieves a guarantor by its `guarantor_id`.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.guarantor.get({
    guarantor_id: "guarantor_id"
});

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

**request:** `Taiga.GetGuarantorRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GuarantorClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.guarantor.<a href="/src/api/resources/guarantor/client/Client.ts">update</a>({ ...params }) -> Taiga.Guarantorv1Guarantor</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates a guarantor by its `guarantor_id`.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.guarantor.update({
    guarantor_id: "guarantor_id",
    body: {}
});

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

**request:** `Taiga.UpdateGuarantorRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GuarantorClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## HealthCareCodeInformation
<details><summary><code>client.healthCareCodeInformation.<a href="/src/api/resources/healthCareCodeInformation/client/Client.ts">listForEncounter</a>({ ...params }) -> Taiga.HealthCareCodeInformationv1HealthCareCodeInformationGetAllResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.healthCareCodeInformation.listForEncounter({
    encounter_id: "encounter_id"
});

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

**request:** `Taiga.ListForEncounterHealthCareCodeInformationRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `HealthCareCodeInformationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.healthCareCodeInformation.<a href="/src/api/resources/healthCareCodeInformation/client/Client.ts">update</a>({ ...params }) -> Taiga.HealthCareCodeInformationv1HealthCareCodeInformationGetAllResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.healthCareCodeInformation.update({
    encounter_id: "encounter_id",
    body: {}
});

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

**request:** `Taiga.UpdateHealthCareCodeInformationRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `HealthCareCodeInformationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## InsuranceRefunds
<details><summary><code>client.insuranceRefunds.<a href="/src/api/resources/insuranceRefunds/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.InsuranceRefundsv1InsuranceRefund, Taiga.InsuranceRefundsv1InsuranceRefundsPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns all insurance refunds satisfying the search criteria AND whose organization_id matches
the current organization_id of the authenticated user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.insuranceRefunds.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.insuranceRefunds.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListInsuranceRefundsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `InsuranceRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.insuranceRefunds.<a href="/src/api/resources/insuranceRefunds/client/Client.ts">create</a>({ ...params }) -> Taiga.InsuranceRefundsv1InsuranceRefund</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates a new insurance refund record and returns the newly created `InsuranceRefund` object.
The allocations can describe whether the refund is being applied toward a specific service line,
claim, or billing provider.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.insuranceRefunds.create({
    payer_identifier: {
        payer_id: "payer_id",
        payer_name: "payer_name",
        type: "payer_info"
    },
    amount_cents: 1,
    allocations: [{
            amount_cents: 1,
            target: {
                type: "service_line_by_id"
            }
        }]
});

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

**request:** `Taiga.InsuranceRefundsv1InsuranceRefundCreate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `InsuranceRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.insuranceRefunds.<a href="/src/api/resources/insuranceRefunds/client/Client.ts">get</a>({ ...params }) -> Taiga.InsuranceRefundsv1InsuranceRefund</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieves a previously created insurance refund by its `insurance_refund_id`.
If the refund does not exist, a `403` will be thrown.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.insuranceRefunds.get({
    insurance_refund_id: "insurance_refund_id"
});

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

**request:** `Taiga.GetInsuranceRefundsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `InsuranceRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.insuranceRefunds.<a href="/src/api/resources/insuranceRefunds/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Deletes the insurance refund record matching the provided `insurance_refund_id`.
If the matching record's organization_id does not match the authenticated user's
current organization_id, then a response code of `403` will be returned.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.insuranceRefunds.delete({
    insurance_refund_id: "insurance_refund_id"
});

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

**request:** `Taiga.DeleteInsuranceRefundsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `InsuranceRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.insuranceRefunds.<a href="/src/api/resources/insuranceRefunds/client/Client.ts">update</a>({ ...params }) -> Taiga.InsuranceRefundsv1InsuranceRefund</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates the patient refund record matching the provided insurance_refund_id. If updating the refund amount,
then the allocations must be appropriately updated as well.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.insuranceRefunds.update({
    insurance_refund_id: "insurance_refund_id"
});

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

**request:** `Taiga.UpdateInsuranceRefundsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `InsuranceRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## NonInsurancePayerPayments
<details><summary><code>client.nonInsurancePayerPayments.<a href="/src/api/resources/nonInsurancePayerPayments/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.NonInsurancePayerPaymentsv1NonInsurancePayerPayment, Taiga.NonInsurancePayerPaymentsv1NonInsurancePayerPaymentsPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns all non-insurance payer payments
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.nonInsurancePayerPayments.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.nonInsurancePayerPayments.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListNonInsurancePayerPaymentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayerPaymentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.nonInsurancePayerPayments.<a href="/src/api/resources/nonInsurancePayerPayments/client/Client.ts">create</a>({ ...params }) -> Taiga.NonInsurancePayerPaymentsv1NonInsurancePayerPayment</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.nonInsurancePayerPayments.create({
    non_insurance_payer_id: "non_insurance_payer_id",
    amount_cents: 1,
    allocations: [{
            amount_cents: 1,
            target: {
                type: "service_line_by_id"
            }
        }]
});

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

**request:** `Taiga.NonInsurancePayerPaymentsv1NonInsurancePayerPaymentCreate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayerPaymentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.nonInsurancePayerPayments.<a href="/src/api/resources/nonInsurancePayerPayments/client/Client.ts">get</a>({ ...params }) -> Taiga.NonInsurancePayerPaymentsv1NonInsurancePayerPayment</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieves a previously created non-insurance payer payment by its `non_insurance_payer_payment_id`.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.nonInsurancePayerPayments.get({
    non_insurance_payer_payment_id: "non_insurance_payer_payment_id"
});

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

**request:** `Taiga.GetNonInsurancePayerPaymentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayerPaymentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.nonInsurancePayerPayments.<a href="/src/api/resources/nonInsurancePayerPayments/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Deletes the non-insurance payer payment record matching the provided `non_insurance_payer_payment_id`.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.nonInsurancePayerPayments.delete({
    non_insurance_payer_payment_id: "non_insurance_payer_payment_id"
});

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

**request:** `Taiga.DeleteNonInsurancePayerPaymentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayerPaymentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.nonInsurancePayerPayments.<a href="/src/api/resources/nonInsurancePayerPayments/client/Client.ts">update</a>({ ...params }) -> Taiga.NonInsurancePayerPaymentsv1NonInsurancePayerPayment</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.nonInsurancePayerPayments.update({
    non_insurance_payer_payment_id: "non_insurance_payer_payment_id"
});

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

**request:** `Taiga.UpdateNonInsurancePayerPaymentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayerPaymentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## NonInsurancePayerRefunds
<details><summary><code>client.nonInsurancePayerRefunds.<a href="/src/api/resources/nonInsurancePayerRefunds/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.NonInsurancePayerRefundsv1NonInsurancePayerRefund, Taiga.NonInsurancePayerRefundsv1NonInsurancePayerRefundsPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns all non-insurance payer refunds satisfying the search criteria
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.nonInsurancePayerRefunds.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.nonInsurancePayerRefunds.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListNonInsurancePayerRefundsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayerRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.nonInsurancePayerRefunds.<a href="/src/api/resources/nonInsurancePayerRefunds/client/Client.ts">create</a>({ ...params }) -> Taiga.NonInsurancePayerRefundsv1NonInsurancePayerRefund</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates a new non-insurance payer refund record and returns the newly created `NonInsurancePayerRefund` object.
The allocations can describe whether the refund is being applied toward a specific service line,
claim, or billing provider.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.nonInsurancePayerRefunds.create({
    non_insurance_payer_id: "non_insurance_payer_id",
    amount_cents: 1,
    allocations: [{
            amount_cents: 1,
            target: {
                type: "service_line_by_id"
            }
        }]
});

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

**request:** `Taiga.NonInsurancePayerRefundsv1NonInsurancePayerRefundCreate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayerRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.nonInsurancePayerRefunds.<a href="/src/api/resources/nonInsurancePayerRefunds/client/Client.ts">get</a>({ ...params }) -> Taiga.NonInsurancePayerRefundsv1NonInsurancePayerRefund</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieves a previously created non-insurance payer refund by its `non_insurance_payer_refund_id`.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.nonInsurancePayerRefunds.get({
    non_insurance_payer_refund_id: "non_insurance_payer_refund_id"
});

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

**request:** `Taiga.GetNonInsurancePayerRefundsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayerRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.nonInsurancePayerRefunds.<a href="/src/api/resources/nonInsurancePayerRefunds/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Deletes the non-insurance payer refund record matching the provided `non_insurance_payer_refund_id`.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.nonInsurancePayerRefunds.delete({
    non_insurance_payer_refund_id: "non_insurance_payer_refund_id"
});

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

**request:** `Taiga.DeleteNonInsurancePayerRefundsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayerRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.nonInsurancePayerRefunds.<a href="/src/api/resources/nonInsurancePayerRefunds/client/Client.ts">update</a>({ ...params }) -> Taiga.NonInsurancePayerRefundsv1NonInsurancePayerRefund</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates the non-insurance payer refund record matching the provided non_insurance_payer_refund_id. If updating the refund amount,
then the allocations must be appropriately updated as well.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.nonInsurancePayerRefunds.update({
    non_insurance_payer_refund_id: "non_insurance_payer_refund_id"
});

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

**request:** `Taiga.UpdateNonInsurancePayerRefundsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayerRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## NonInsurancePayers
<details><summary><code>client.nonInsurancePayers.<a href="/src/api/resources/nonInsurancePayers/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.NonInsurancePayersv1NonInsurancePayer, Taiga.NonInsurancePayersv1NonInsurancePayerPage&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.nonInsurancePayers.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.nonInsurancePayers.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListNonInsurancePayersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.nonInsurancePayers.<a href="/src/api/resources/nonInsurancePayers/client/Client.ts">create</a>({ ...params }) -> Taiga.NonInsurancePayersv1NonInsurancePayer</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.nonInsurancePayers.create({
    name: "name"
});

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

**request:** `Taiga.NonInsurancePayersv1CreateNonInsurancePayerRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.nonInsurancePayers.<a href="/src/api/resources/nonInsurancePayers/client/Client.ts">toggleEnablement</a>({ ...params }) -> Taiga.NonInsurancePayersv1NonInsurancePayer</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.nonInsurancePayers.toggleEnablement({
    non_insurance_payer_id: "non_insurance_payer_id",
    enabled: true
});

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

**request:** `Taiga.NonInsurancePayersv1ToggleNonInsurancePayerEnablementRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.nonInsurancePayers.<a href="/src/api/resources/nonInsurancePayers/client/Client.ts">getCategories</a>({ ...params }) -> core.Page&lt;string, Taiga.NonInsurancePayersv1NonInsurancePayerCategoriesPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns a paginated list of all non-insurance payer categories.

Non-insurance payer categories are simply strings and are not stored as a
separate object in Taiga. They are created when added to at least one
non-insurance payer's `category` field and are deleted when there are no
longer any non-insurance payers that contain them.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.nonInsurancePayers.getCategories();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.nonInsurancePayers.getCategories();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.GetCategoriesNonInsurancePayersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.nonInsurancePayers.<a href="/src/api/resources/nonInsurancePayers/client/Client.ts">get</a>({ ...params }) -> Taiga.NonInsurancePayersv1NonInsurancePayer</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.nonInsurancePayers.get({
    non_insurance_payer_id: "non_insurance_payer_id"
});

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

**request:** `Taiga.GetNonInsurancePayersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.nonInsurancePayers.<a href="/src/api/resources/nonInsurancePayers/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.nonInsurancePayers.delete({
    non_insurance_payer_id: "non_insurance_payer_id"
});

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

**request:** `Taiga.DeleteNonInsurancePayersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.nonInsurancePayers.<a href="/src/api/resources/nonInsurancePayers/client/Client.ts">update</a>({ ...params }) -> Taiga.NonInsurancePayersv1NonInsurancePayer</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.nonInsurancePayers.update({
    non_insurance_payer_id: "non_insurance_payer_id"
});

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

**request:** `Taiga.NonInsurancePayersv1NonInsurancePayerUpdateRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NonInsurancePayersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## OrganizationProviders
<details><summary><code>client.organizationProviders.<a href="/src/api/resources/organizationProviders/client/Client.ts">get</a>({ ...params }) -> Taiga.OrganizationProvidersv3OrganizationProviderV2</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.organizationProviders.get({
    organization_provider_id: "organization_provider_id"
});

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

**request:** `Taiga.GetOrganizationProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.organizationProviders.<a href="/src/api/resources/organizationProviders/client/Client.ts">update</a>({ ...params }) -> Taiga.OrganizationProvidersv3OrganizationProviderV2</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.organizationProviders.update({
    organization_provider_id: "organization_provider_id"
});

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

**request:** `Taiga.OrganizationProvidersv3OrganizationProviderUpdateV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.organizationProviders.<a href="/src/api/resources/organizationProviders/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.OrganizationProvidersv3OrganizationProviderV2, Taiga.OrganizationProvidersv3OrganizationProviderPageV2&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.organizationProviders.list({
    search_term: "john",
    npi: "1234567890"
});
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.organizationProviders.list({
    search_term: "john",
    npi: "1234567890"
});
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListOrganizationProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.organizationProviders.<a href="/src/api/resources/organizationProviders/client/Client.ts">create</a>({ ...params }) -> Taiga.OrganizationProvidersv3OrganizationProviderV2</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.organizationProviders.create({
    npi: "npi",
    is_rendering: true,
    is_billing: true,
    provider_type: "INDIVIDUAL",
    license_type: "MD",
    qualifications: [{
            identifier_code: "MCR",
            identifier_value: {
                state: "AA",
                provider_number: "provider_number",
                type: "medicare_provider_identifier"
            }
        }]
});

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

**request:** `Taiga.OrganizationProvidersv3OrganizationProviderCreateV2` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.organizationProviders.<a href="/src/api/resources/organizationProviders/client/Client.ts">listAttachments</a>({ ...params }) -> Taiga.OrganizationProvidersv3ProviderAttachment[]</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.organizationProviders.listAttachments({
    organization_provider_id: "organization_provider_id"
});

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

**request:** `Taiga.ListAttachmentsOrganizationProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.organizationProviders.<a href="/src/api/resources/organizationProviders/client/Client.ts">uploadAttachment</a>({ ...params }) -> Taiga.OrganizationProvidersv3ProviderAttachmentId</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Uploads a file to the provider. Accepted file types are W9, PECOS_RECORD, and BANK_LETTER_OR_VOIDED_CHECK.
Only one file per type is allowed per provider — uploading when a file of the same type already exists returns a 409.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.organizationProviders.uploadAttachment({
    organization_provider_id: "organization_provider_id"
});

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

**request:** `Taiga.UploadAttachmentOrganizationProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.organizationProviders.<a href="/src/api/resources/organizationProviders/client/Client.ts">downloadAttachment</a>({ ...params }) -> Taiga.OrganizationProvidersv3ProviderAttachmentResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.organizationProviders.downloadAttachment({
    attachment_id: "attachment_id"
});

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

**request:** `Taiga.DownloadAttachmentOrganizationProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.organizationProviders.<a href="/src/api/resources/organizationProviders/client/Client.ts">deleteAttachment</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.organizationProviders.deleteAttachment({
    attachment_id: "attachment_id"
});

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

**request:** `Taiga.DeleteAttachmentOrganizationProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## OrganizationServiceFacilities
<details><summary><code>client.organizationServiceFacilities.<a href="/src/api/resources/organizationServiceFacilities/client/Client.ts">get</a>({ ...params }) -> Taiga.OrganizationServiceFacilitiesv2OrganizationServiceFacility</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.organizationServiceFacilities.get({
    organization_service_facility_id: "organization_service_facility_id"
});

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

**request:** `Taiga.GetOrganizationServiceFacilitiesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationServiceFacilitiesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.organizationServiceFacilities.<a href="/src/api/resources/organizationServiceFacilities/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.organizationServiceFacilities.delete({
    organization_service_facility_id: "organization_service_facility_id"
});

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

**request:** `Taiga.DeleteOrganizationServiceFacilitiesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationServiceFacilitiesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.organizationServiceFacilities.<a href="/src/api/resources/organizationServiceFacilities/client/Client.ts">update</a>({ ...params }) -> Taiga.OrganizationServiceFacilitiesv2OrganizationServiceFacility</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.organizationServiceFacilities.update({
    organization_service_facility_id: "organization_service_facility_id",
    name: "Test Service Facility",
    aliases: ["Test Service Facility Alias"],
    description: "Test Service Facility Description",
    status: "active",
    operational_status: "C",
    mode: "instance",
    type: "DX",
    physical_type: "si",
    telecoms: ["555-555-5555"],
    address: {
        address1: "123 Main St",
        address2: "Apt 1",
        city: "New York",
        state: "NY",
        zip_code: "10001",
        zip_plus_four_code: "1234"
    }
});

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

**request:** `Taiga.OrganizationServiceFacilitiesv2OrganizationServiceFacilityUpdate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationServiceFacilitiesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.organizationServiceFacilities.<a href="/src/api/resources/organizationServiceFacilities/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.OrganizationServiceFacilitiesv2OrganizationServiceFacility, Taiga.OrganizationServiceFacilitiesv2OrganizationServiceFacilityPage&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.organizationServiceFacilities.list({
    name: "Test Service Facility"
});
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.organizationServiceFacilities.list({
    name: "Test Service Facility"
});
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListOrganizationServiceFacilitiesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationServiceFacilitiesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.organizationServiceFacilities.<a href="/src/api/resources/organizationServiceFacilities/client/Client.ts">create</a>({ ...params }) -> Taiga.OrganizationServiceFacilitiesv2OrganizationServiceFacility</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.organizationServiceFacilities.create({
    name: "Test Service Facility",
    aliases: ["Test Service Facility Alias"],
    description: "Test Service Facility Description",
    status: "active",
    operational_status: "C",
    mode: "instance",
    type: "DX",
    physical_type: "si",
    telecoms: ["555-555-5555"],
    address: {
        address1: "123 Main St",
        address2: "Apt 1",
        city: "New York",
        state: "NY",
        zip_code: "10001",
        zip_plus_four_code: "1234"
    }
});

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

**request:** `Taiga.OrganizationServiceFacilitiesv2OrganizationServiceFacilityCreate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationServiceFacilitiesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.organizationServiceFacilities.<a href="/src/api/resources/organizationServiceFacilities/client/Client.ts">getByExternalId</a>({ ...params }) -> Taiga.OrganizationServiceFacilitiesv2OrganizationServiceFacility</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Looks up a single organization service facility by its `external_id` field. This can be useful
for finding service facilities within Taiga which are associated with service facilities in
an external system.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.organizationServiceFacilities.getByExternalId({
    external_id: "external_id"
});

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

**request:** `Taiga.GetByExternalIdOrganizationServiceFacilitiesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationServiceFacilitiesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PatientPayments
<details><summary><code>client.patientPayments.<a href="/src/api/resources/patientPayments/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.PatientPaymentsv4PatientPayment, Taiga.PatientPaymentsv4PatientPaymentsPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns all patient payments satisfying the search criteria AND whose organization_id matches
the current organization_id of the authenticated user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.patientPayments.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.patientPayments.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListPatientPaymentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientPaymentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.patientPayments.<a href="/src/api/resources/patientPayments/client/Client.ts">create</a>({ ...params }) -> Taiga.PatientPaymentsv4PatientPayment</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Records an already-collected patient payment. Each request may contain only claim_by_id allocations or only appointment_by_id_and_patient_external_id allocations; mixed target types are rejected. unattributed, service_line_by_id, claim_by_encounter_external_id, billing_provider_by_id, and malformed targets are unsupported. Claim and appointment payments require 1–25 positive allocations, a verified financial patient MRN, and exactly one in-scope billing_provider_npi allocation restriction; any service_facility_id restriction must also be in scope. Each claim must match both the patient and restricted NPI; every appointment must belong to the patient. For claim and appointment payments, unknown fields and invalid scope or target proofs are refused with 403 before creating a payment. See [Creating patient payments](/patient-payments) for requirements and a minimal request.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.patientPayments.create({
    allocation_restrictions: [{
            restriction_type: "billing_provider_npi",
            restriction_value: "1234567893"
        }],
    allocations: [{
            amount_cents: 2500,
            target: {
                type: "claim_by_id",
                value: "11111111-1111-4111-8111-111111111111"
            }
        }],
    amount_cents: 2500,
    patient_external_id: "PATIENT-123"
});

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

**request:** `Taiga.CreatePatientPaymentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientPaymentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.patientPayments.<a href="/src/api/resources/patientPayments/client/Client.ts">get</a>({ ...params }) -> Taiga.PatientPaymentsv4PatientPayment</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieves a previously created patient payment by its `patient_payment_id`.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.patientPayments.get({
    patient_payment_id: "patient_payment_id"
});

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

**request:** `Taiga.GetPatientPaymentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientPaymentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.patientPayments.<a href="/src/api/resources/patientPayments/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Deletes the patient payment record matching the provided patient_payment_id.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.patientPayments.delete({
    patient_payment_id: "patient_payment_id"
});

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

**request:** `Taiga.DeletePatientPaymentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientPaymentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.patientPayments.<a href="/src/api/resources/patientPayments/client/Client.ts">update</a>({ ...params }) -> Taiga.PatientPaymentsv4PatientPayment</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates the patient payment record matching the provided patient_payment_id.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.patientPayments.update({
    patient_payment_id: "patient_payment_id"
});

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

**request:** `Taiga.UpdatePatientPaymentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientPaymentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PatientRefunds
<details><summary><code>client.patientRefunds.<a href="/src/api/resources/patientRefunds/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.PatientRefundsv1PatientRefund, Taiga.PatientRefundsv1PatientRefundsPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns all patient refunds satisfying the search criteria AND whose organization_id matches
the current organization_id of the authenticated user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.patientRefunds.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.patientRefunds.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListPatientRefundsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.patientRefunds.<a href="/src/api/resources/patientRefunds/client/Client.ts">create</a>({ ...params }) -> Taiga.PatientRefundsv1PatientRefund</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates a new patient refund record and returns the newly created PatientRefund object.
The allocations can describe whether the refund is being applied toward a specific service line,
claim, or billing provider.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.patientRefunds.create({
    amount_cents: 1,
    patient_external_id: "patient_external_id",
    allocations: [{
            amount_cents: 1,
            target: {
                type: "service_line_by_id"
            }
        }]
});

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

**request:** `Taiga.CreatePatientRefundsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.patientRefunds.<a href="/src/api/resources/patientRefunds/client/Client.ts">get</a>({ ...params }) -> Taiga.PatientRefundsv1PatientRefund</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieves a previously created patient refund by its `patient_refund_id`.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.patientRefunds.get({
    patient_refund_id: "patient_refund_id"
});

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

**request:** `Taiga.GetPatientRefundsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.patientRefunds.<a href="/src/api/resources/patientRefunds/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Deletes the patient refund record matching the provided patient_refund_id.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.patientRefunds.delete({
    patient_refund_id: "patient_refund_id"
});

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

**request:** `Taiga.DeletePatientRefundsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.patientRefunds.<a href="/src/api/resources/patientRefunds/client/Client.ts">update</a>({ ...params }) -> Taiga.PatientRefundsv1PatientRefund</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates the patient refund record matching the provided patient_refund_id.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.patientRefunds.update({
    patient_refund_id: "patient_refund_id"
});

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

**request:** `Taiga.UpdatePatientRefundsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientRefundsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Payers
<details><summary><code>client.payers.<a href="/src/api/resources/payers/client/Client.ts">get</a>({ ...params }) -> Taiga.Payersv4Payer</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.payers.get({
    payer_uuid: "payer_uuid"
});

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

**request:** `Taiga.GetPayersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PayersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payers.<a href="/src/api/resources/payers/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.Payersv4Payer, Taiga.Payersv4PayerPage&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.payers.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.payers.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListPayersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PayersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PreServiceRules
<details><summary><code>client.preServiceRules.<a href="/src/api/resources/preServiceRules/client/Client.ts">createEncounterRun</a>({ ...params }) -> Taiga.PreServiceRulesv1PreServiceRunId</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Submit a representation of an encounter to the Taiga rules engine. Note that this encounter will not be created in Taiga.
Returns a run_id that can be polled via GET /runs/{run_id} to retrieve the results once complete.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preServiceRules.createEncounterRun({
    entity: {
        external_id: "enc-123",
        patient_authorized_release: true,
        benefits_assigned_to_provider: true,
        provider_accepts_assignment: true,
        patient: {
            first_name: "Jane",
            last_name: "Doe",
            gender: "female",
            external_id: "p-456",
            date_of_birth: "1960-01-01",
            address: {
                address1: "1 Main St",
                city: "Fairfax",
                state: "VA",
                zip_code: "22031"
            }
        },
        responsible_party: "INSURANCE_PAY",
        billing_provider: {
            organization_name: "Example Clinic",
            address: {
                address1: "1 Main St",
                city: "Fairfax",
                state: "VA",
                zip_code: "22031",
                zip_plus_four_code: "4634"
            },
            tax_id: "202265068",
            npi: "1558375857"
        },
        submission_expectation: "TARGET_PROFESSIONAL",
        date_of_service: "2026-10-15",
        subscriber_primary: {
            first_name: "Jane",
            last_name: "Doe",
            gender: "female",
            patient_relationship_to_subscriber_code: "18",
            insurance_card: {
                member_id: "123456789",
                payer_name: "Example Payer",
                payer_id: "12345"
            }
        },
        rendering_provider: {
            first_name: "Ada",
            last_name: "Lovelace",
            npi: "1234567893"
        },
        service_lines: [{
                quantity: "1",
                units: "UN",
                charge_amount_cents: 20600,
                diagnosis_pointers: [0],
                procedure_code: "99213"
            }],
        health_care_code_information: {
            principal_diagnosis: {
                principal_diagnosis_code_qualifier: "ABK",
                primary_diagnosis_code: "Z01.411"
            }
        }
    },
    pipeline_id: "pre-service-claim-athena",
    enabled_rule_ids: ["enabled_rule_ids"],
    disabled_rule_ids: ["disabled_rule_ids"],
    idempotency_key: "enc-123-run-1"
});

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

**request:** `Taiga.CreateEncounterRunPreServiceRulesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PreServiceRulesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## ServiceLines
<details><summary><code>client.serviceLines.<a href="/src/api/resources/serviceLines/client/Client.ts">create</a>({ ...params }) -> Taiga.ServiceLinesv2ServiceLine</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.serviceLines.create({
    quantity: "quantity",
    units: "MJ",
    claim_id: "claim_id",
    procedure_code: "procedure_code"
});

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

**request:** `Taiga.ServiceLinesv2ServiceLineCreateStandalone` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ServiceLinesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.serviceLines.<a href="/src/api/resources/serviceLines/client/Client.ts">createUniversal</a>({ ...params }) -> Taiga.ServiceLinesv2ServiceLine</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.serviceLines.createUniversal({
    quantity: "quantity",
    units: "MJ",
    claim_id: "claim_id"
});

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

**request:** `Taiga.ServiceLinesv2UniversalServiceLineCreateStandalone` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ServiceLinesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.serviceLines.<a href="/src/api/resources/serviceLines/client/Client.ts">updateUniversal</a>({ ...params }) -> Taiga.ServiceLinesv2ServiceLine</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.serviceLines.updateUniversal({
    service_line_id: "service_line_id"
});

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

**request:** `Taiga.ServiceLinesv2UniversalServiceLineUpdate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ServiceLinesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.serviceLines.<a href="/src/api/resources/serviceLines/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.serviceLines.delete({
    service_line_id: "service_line_id"
});

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

**request:** `Taiga.DeleteServiceLinesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ServiceLinesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.serviceLines.<a href="/src/api/resources/serviceLines/client/Client.ts">update</a>({ ...params }) -> Taiga.ServiceLinesv2ServiceLine</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.serviceLines.update({
    service_line_id: "service_line_id"
});

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

**request:** `Taiga.ServiceLinesv2ServiceLineUpdate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ServiceLinesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Tasks
<details><summary><code>client.tasks.<a href="/src/api/resources/tasks/client/Client.ts">getActions</a>({ ...params }) -> Taiga.Tasksv3TaskActions</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.tasks.getActions({
    task_id: "task_id"
});

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

**request:** `Taiga.GetActionsTasksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TasksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.tasks.<a href="/src/api/resources/tasks/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.Tasksv3Task, Taiga.Tasksv3TaskPage&gt;</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.tasks.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.tasks.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.ListTasksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TasksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.tasks.<a href="/src/api/resources/tasks/client/Client.ts">get</a>({ ...params }) -> Taiga.Tasksv3Task</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.tasks.get({
    task_id: "task_id"
});

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

**request:** `Taiga.GetTasksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TasksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.tasks.<a href="/src/api/resources/tasks/client/Client.ts">update</a>({ ...params }) -> Taiga.Tasksv3Task</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates a task on one of your encounters. Set `status` to `addressed_by_provider_group` once you have supplied or corrected the data the task requested; the billing team then re-reviews the claim. Status transitions are validated upstream and an invalid transition returns 4xx. A task you cannot reach returns 404.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.tasks.update({
    task_id: "task_id"
});

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

**request:** `Taiga.Tasksv3TaskUpdateV3` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TasksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Diagnoses
<details><summary><code>client.diagnoses.<a href="/src/api/resources/diagnoses/client/Client.ts">create</a>({ ...params }) -> Taiga.Diagnosis</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates a new diagnosis for an encounter
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.diagnoses.create({
    code_type: "ABF",
    code: "code",
    encounter_id: "encounter_id"
});

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

**request:** `Taiga.StandaloneDiagnosisCreate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DiagnosesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.diagnoses.<a href="/src/api/resources/diagnoses/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Deletes the diagnosis record associated with the provided `diagnosis_id`
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.diagnoses.delete({
    diagnosis_id: "diagnosis_id"
});

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

**request:** `Taiga.DeleteDiagnosesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DiagnosesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.diagnoses.<a href="/src/api/resources/diagnoses/client/Client.ts">update</a>({ ...params }) -> Taiga.Diagnosis</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates the diagnosis record matching the provided `diagnosis_id`
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.diagnoses.update({
    diagnosis_id: "diagnosis_id"
});

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

**request:** `Taiga.UpdateDiagnosesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DiagnosesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PriorAuthorizations
<details><summary><code>client.priorAuthorizations.<a href="/src/api/resources/priorAuthorizations/client/Client.ts">list</a>({ ...params }) -> Taiga.ListPriorAuthorizationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Lists prior-authorization requests in the credential's billing-provider scope. Use external_id for idempotent reconciliation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.priorAuthorizations.list();

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

**request:** `Taiga.ListPriorAuthorizationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PriorAuthorizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.priorAuthorizations.<a href="/src/api/resources/priorAuthorizations/client/Client.ts">create</a>({ ...params }) -> Taiga.PriorAuthorization</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Queues a managed prior-authorization request for review and payer-portal submission. A 202 response means the request was received; it does not mean it was submitted to the payer.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.priorAuthorizations.create({
    service_type: "COMMUNITY_SUPPORTS",
    billing_provider_npi: "billing_provider_npi",
    coverage_id: "coverage_id",
    external_id: "external_id",
    patient_id: "patient_id",
    ecm_enrollment: true,
    services: [{
            chronic_conditions: ["DIABETES"],
            discharge_or_high_risk: true,
            extensive_care_coordination_needs: true,
            mtm_types: ["HOME_DELIVERED_MEALS"],
            service: "MEDICALLY_TAILORED_MEALS"
        }]
});

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

**request:** `Taiga.PriorAuthorizationCreate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PriorAuthorizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.priorAuthorizations.<a href="/src/api/resources/priorAuthorizations/client/Client.ts">getWebhook</a>() -> Taiga.PriorAuthorizationWebhookEndpoint</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.priorAuthorizations.getWebhook();

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

**requestOptions:** `PriorAuthorizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.priorAuthorizations.<a href="/src/api/resources/priorAuthorizations/client/Client.ts">configureWebhook</a>({ ...params }) -> Taiga.PriorAuthorizationWebhookEndpoint</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Registers one HTTPS callback for the organization. Status events are signed and retried with exponential backoff.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.priorAuthorizations.configureWebhook({
    url: "url"
});

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

**request:** `Taiga.ConfigureWebhookPriorAuthorizationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PriorAuthorizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.priorAuthorizations.<a href="/src/api/resources/priorAuthorizations/client/Client.ts">disableWebhook</a>() -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.priorAuthorizations.disableWebhook();

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

**requestOptions:** `PriorAuthorizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.priorAuthorizations.<a href="/src/api/resources/priorAuthorizations/client/Client.ts">replayWebhook</a>({ ...params }) -> Taiga.PriorAuthorizationWebhookDelivery</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Requeues one abandoned webhook event for this organization and resets its retry counter. Only ABANDONED events can be replayed.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.priorAuthorizations.replayWebhook({
    event_id: "event_id"
});

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

**request:** `Taiga.PriorAuthorizationWebhookReplayRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PriorAuthorizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.priorAuthorizations.<a href="/src/api/resources/priorAuthorizations/client/Client.ts">testWebhook</a>() -> Taiga.PriorAuthorizationWebhookDelivery</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Enqueues a signed webhook_test event with an empty data object. It contains no patient or authorization data and uses the normal delivery and retry path.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.priorAuthorizations.testWebhook();

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

**requestOptions:** `PriorAuthorizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.priorAuthorizations.<a href="/src/api/resources/priorAuthorizations/client/Client.ts">get</a>({ ...params }) -> Taiga.PriorAuthorization</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.priorAuthorizations.get({
    id: "id"
});

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

**request:** `Taiga.GetPriorAuthorizationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PriorAuthorizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.priorAuthorizations.<a href="/src/api/resources/priorAuthorizations/client/Client.ts">triggerTestStatus</a>({ ...params }) -> Taiga.PriorAuthorization</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sets a deterministic outcome on a request created with test_mode=true and enqueues the same signed webhook used by live status changes. Ordinary requests cannot use this endpoint. A terminal test outcome cannot be changed; create a separate test request for each terminal scenario. See [test statuses and webhook examples](/docs/prior-authorization-webhooks).
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.priorAuthorizations.triggerTestStatus({
    id: "id",
    body: {
        status: "DENIED"
    }
});

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

**request:** `Taiga.TriggerTestStatusPriorAuthorizationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PriorAuthorizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.priorAuthorizations.<a href="/src/api/resources/priorAuthorizations/client/Client.ts">listV2</a>({ ...params }) -> Taiga.ListV2PriorAuthorizationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Lists managed authorizations, including podiatry, in the credential's billing-provider scope.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.priorAuthorizations.listV2();

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

**request:** `Taiga.ListV2PriorAuthorizationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PriorAuthorizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.priorAuthorizations.<a href="/src/api/resources/priorAuthorizations/client/Client.ts">createV2</a>({ ...params }) -> Taiga.PriorAuthorizationV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Queues a managed prior-authorization request for review and payer-portal submission. A 202 response means the request was received; it does not mean it was submitted to the payer.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.priorAuthorizations.createV2({
    service_type: "COMMUNITY_SUPPORTS",
    billing_provider_npi: "billing_provider_npi",
    coverage_id: "coverage_id",
    external_id: "external_id",
    patient_id: "patient_id",
    ecm_enrollment: true,
    services: [{
            chronic_conditions: ["DIABETES"],
            discharge_or_high_risk: true,
            extensive_care_coordination_needs: true,
            mtm_types: ["HOME_DELIVERED_MEALS"],
            service: "MEDICALLY_TAILORED_MEALS"
        }]
});

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

**request:** `Taiga.PriorAuthorizationV2Create` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PriorAuthorizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.priorAuthorizations.<a href="/src/api/resources/priorAuthorizations/client/Client.ts">getV2</a>({ ...params }) -> Taiga.PriorAuthorizationV2</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.priorAuthorizations.getV2({
    id: "id"
});

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

**request:** `Taiga.GetV2PriorAuthorizationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PriorAuthorizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.priorAuthorizations.<a href="/src/api/resources/priorAuthorizations/client/Client.ts">triggerTestStatusV2</a>({ ...params }) -> Taiga.PriorAuthorizationV2</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sets a deterministic outcome on a request created with test_mode=true and enqueues the same signed webhook used by live status changes. Ordinary requests cannot use this endpoint. A terminal test outcome cannot be changed; create a separate test request for each terminal scenario. See [test statuses and webhook examples](/docs/prior-authorization-webhooks).
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.priorAuthorizations.triggerTestStatusV2({
    id: "id",
    body: {
        status: "DENIED"
    }
});

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

**request:** `Taiga.TriggerTestStatusV2PriorAuthorizationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PriorAuthorizationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Prices
<details><summary><code>client.prices.<a href="/src/api/resources/prices/client/Client.ts">create</a>({ ...params }) -> Taiga.Price</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Prices a visit's patient responsibility before it happens. Pricing must be enabled for the credential's organization in the target environment. Answers 200 with the finished price, or 202 while it is still processing; use [price readback](/api-reference/prices/get-price) to check its status.

For staging, send the sandbox example below to `https://api-staging.taigabilling.com` with a staging API key and a `billing_provider_npi` in its scope. Use sandbox payer `SBX01` and member `SBX-ACTIVE` for an active-coverage test; find supported payer identifiers with [payer lookup](/api-reference/prices/list-price-payers). A sandbox price has `livemode: false`.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.prices.create({
    "Idempotency-Key": "Idempotency-Key",
    billing_provider_npi: "1669095808",
    insurances: [{
            member_id: "W123456789",
            payer_id: "60054",
            state: "NY"
        }],
    items: [{
            code: "99213",
            modifiers: ["modifiers"]
        }, {
            code: "80053",
            modifiers: ["modifiers"]
        }],
    patient: {
        dob: "1984-04-04",
        first_name: "Jane",
        last_name: "Doe",
        reference: "patient-001"
    },
    provider: {
        last_name: "Smith",
        npi: "1234567893"
    }
});

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

**request:** `Taiga.PriceCreate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PricesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.prices.<a href="/src/api/resources/prices/client/Client.ts">listPayers</a>({ ...params }) -> Taiga.PayerList</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Searches the payers supported for pricing. Send a payer's `id`, any alias `value` or its exact name as `payer_id`.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.prices.listPayers();

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

**request:** `Taiga.ListPayersPricesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PricesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.prices.<a href="/src/api/resources/prices/client/Client.ts">resolvePayers</a>({ ...params }) -> Taiga.PayerResolution</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Matches up to 200 payer names from your system to pricing payer ids. Read-only and safe to retry.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.prices.resolvePayers({
    queries: ["queries"]
});

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

**request:** `Taiga.PayerResolveRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PricesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.prices.<a href="/src/api/resources/prices/client/Client.ts">createTreatmentPrediction</a>({ ...params }) -> Taiga.TreatmentPrediction</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Predicts the procedure codes for an upcoming visit without pricing it. Price the result by sending its `id` as `treatments.trt_id` to the create-price endpoint.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.prices.createTreatmentPrediction({
    "Idempotency-Key": "Idempotency-Key",
    appointment: {
        type: "type"
    },
    billing_provider_npi: "billing_provider_npi",
    patient: {
        reference: "reference"
    }
});

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

**request:** `Taiga.TreatmentPredictionCreate` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PricesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.prices.<a href="/src/api/resources/prices/client/Client.ts">get</a>({ ...params }) -> Taiga.Price</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.prices.get({
    price_id: "price_id"
});

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

**request:** `Taiga.GetPricesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PricesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## ManualClaims
<details><summary><code>client.manualClaims.<a href="/src/api/resources/manualClaims/client/Client.ts">get</a>({ ...params }) -> Taiga.ManualClaimDetails</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Reads a saved manual submission request and its intake snapshots. Only the creating clinic and its currently scoped billing provider can read it. This is a manual-review receipt, not confirmation of payer submission.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.manualClaims.get({
    manual_claim_id: "manual_claim_id"
});

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

**request:** `Taiga.GetManualClaimsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ManualClaimsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PreEncounter Appointments
<details><summary><code>client.preEncounter.appointments.<a href="/src/api/resources/preEncounter/resources/appointments/client/Client.ts">create</a>({ ...params }) -> Taiga.PreEncounterappointmentsv1Appointment</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Adds an appointment.  VersionConflictError is returned when the placer_appointment_id is already in use.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.appointments.create({
    patient_id: "patient_id",
    start_timestamp: "2024-01-15T09:30:00Z",
    service_duration: 1,
    services: [{}]
});

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

**request:** `Taiga.PreEncounterappointmentsv1MutableAppointment` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AppointmentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.appointments.<a href="/src/api/resources/preEncounter/resources/appointments/client/Client.ts">getVisits</a>({ ...params }) -> core.Page&lt;Taiga.PreEncounterappointmentsv1Visit, Taiga.PreEncounterappointmentsv1VisitsPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets all Visits within a given time range. The return list is ordered by start_time ascending.

**IMPORTANT:** This endpoint requires a date filter on `appointment.startTimestamp` to ensure acceptable query performance.
Without date filtering, the query can take 50+ seconds on large datasets due to grouping and aggregation operations.

Example filters:
- `appointment.startTimestamp|gt|2024-01-01` - appointments after January 1, 2024
- `appointment.startTimestamp|eq|2024-12-08` - appointments on December 8, 2024
- `appointment.startTimestamp|lt|2024-12-31` - appointments before December 31, 2024

You can combine the date filter with other filters using commas:
- `appointment.startTimestamp|gt|2024-01-01,appointment.status|eq|PENDING`
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.preEncounter.appointments.getVisits();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.preEncounter.appointments.getVisits();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.preEncounter.GetVisitsAppointmentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AppointmentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.appointments.<a href="/src/api/resources/preEncounter/resources/appointments/client/Client.ts">getCounts</a>({ ...params }) -> Taiga.PreEncounterappointmentsv1CountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets aggregate counts for the visits matching the given filters.

The counts respect all provided filters but are independent of pagination, so this can be fetched
once when filters change instead of on every page of `get_visits`.

**IMPORTANT:** Like `get_visits`, this endpoint requires a date filter on `appointment.startTimestamp`
to ensure acceptable query performance.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.appointments.getCounts();

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

**request:** `Taiga.preEncounter.GetCountsAppointmentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AppointmentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.appointments.<a href="/src/api/resources/preEncounter/resources/appointments/client/Client.ts">get</a>({ ...params }) -> Taiga.PreEncounterappointmentsv1Appointment</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets an appointment.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.appointments.get({
    id: "id"
});

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

**request:** `Taiga.preEncounter.GetAppointmentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AppointmentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.appointments.<a href="/src/api/resources/preEncounter/resources/appointments/client/Client.ts">getHistory</a>({ ...params }) -> Taiga.PreEncounterappointmentsv1Appointment[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets an appointment along with it's full history.  The return list is ordered by version ascending.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.appointments.getHistory({
    id: "id"
});

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

**request:** `Taiga.preEncounter.GetHistoryAppointmentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AppointmentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.appointments.<a href="/src/api/resources/preEncounter/resources/appointments/client/Client.ts">update</a>({ ...params }) -> Taiga.PreEncounterappointmentsv1Appointment</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates an appointment. The path must contain the next version number to prevent race conditions. For example, if the current version of the appointment is n, you will need to send a request to this endpoint with `/{id}/n+1` to update the appointment. Updating historic versions is not supported.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.appointments.update({
    id: "id",
    version: "version",
    body: {
        patient_id: "patient_id",
        start_timestamp: "2024-01-15T09:30:00Z",
        service_duration: 1,
        services: [{}]
    }
});

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

**request:** `Taiga.preEncounter.UpdateAppointmentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AppointmentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.appointments.<a href="/src/api/resources/preEncounter/resources/appointments/client/Client.ts">deactivate</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sets an appointment as deactivated.  The path must contain the most recent version to prevent race conditions.  Deactivating historic versions is not supported. Subsequent updates via PUT to the appointment will "reactivate" the appointment, set the deactivated flag to false, and clear the cancellation reason.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.appointments.deactivate({
    id: "id",
    version: "version"
});

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

**request:** `Taiga.preEncounter.DeactivateAppointmentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AppointmentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.appointments.<a href="/src/api/resources/preEncounter/resources/appointments/client/Client.ts">scan</a>({ ...params }) -> Taiga.PreEncounterappointmentsv1Appointment[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Scans up to 100 appointment updates.  The since query parameter is inclusive, and the result list is ordered by updatedAt ascending.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.appointments.scan({
    since: "2024-01-15T09:30:00Z"
});

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

**request:** `Taiga.preEncounter.ScanAppointmentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AppointmentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PreEncounter Coverages
<details><summary><code>client.preEncounter.coverages.<a href="/src/api/resources/preEncounter/resources/coverages/client/Client.ts">list</a>({ ...params }) -> Taiga.PreEncountercoveragesv1Coverage[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns a page of Coverages based on the search criteria. `patient_id` is optional; when it is omitted or empty the response contains every coverage created by your organization through this API, unfiltered. Filtering by `patient_id` is the supported way to read one patient's coverages.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.coverages.list();

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

**request:** `Taiga.preEncounter.ListCoveragesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CoveragesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.coverages.<a href="/src/api/resources/preEncounter/resources/coverages/client/Client.ts">create</a>({ ...params }) -> Taiga.PreEncountercoveragesv1Coverage</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates a new Coverage. A Coverage provides the high-level identifiers and descriptors of a specific insurance plan for a specific individual - typically the information you can find on an insurance card. Additionally a coverage will include detailed benefits information covered by the specific plan for the individual.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.coverages.create({
    status: "ACTIVE",
    subscriber: {
        name: {
            family: "family",
            given: ["given"],
            use: "USUAL"
        },
        biological_sex: "FEMALE"
    },
    relationship: "SELF",
    patient: "patient",
    insurance_plan: {
        member_id: "member_id",
        payer_id: "payer_id",
        payer_name: "payer_name"
    },
    verified: true
});

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

**request:** `Taiga.PreEncountercoveragesv1MutableCoverage` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CoveragesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.coverages.<a href="/src/api/resources/preEncounter/resources/coverages/client/Client.ts">update</a>({ ...params }) -> Taiga.PreEncountercoveragesv1Coverage</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates a Coverage. The path must contain the next version number to prevent race conditions. For example, if the current version of the coverage is n, you will need to send a request to this endpoint with `/{id}/n+1` to update the coverage. Updating historic versions is not supported.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.coverages.update({
    id: "id",
    version: "version",
    body: {
        status: "ACTIVE",
        subscriber: {
            name: {
                family: "family",
                given: ["given"],
                use: "USUAL"
            },
            biological_sex: "FEMALE"
        },
        relationship: "SELF",
        patient: "patient",
        insurance_plan: {
            member_id: "member_id",
            payer_id: "payer_id",
            payer_name: "payer_name"
        },
        verified: true
    }
});

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

**request:** `Taiga.preEncounter.UpdateCoveragesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CoveragesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.coverages.<a href="/src/api/resources/preEncounter/resources/coverages/client/Client.ts">listPaginated</a>({ ...params }) -> core.Page&lt;Taiga.PreEncountercoveragesv1Coverage, Taiga.PreEncountercoveragesv1CoveragesPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns a page of Coverages based on the search criteria. `patient_id` is optional; when it is omitted or empty the response contains every coverage created by your organization through this API, unfiltered. Filtering by `patient_id` is the supported way to read one patient's coverages.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.preEncounter.coverages.listPaginated();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.preEncounter.coverages.listPaginated();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.preEncounter.ListPaginatedCoveragesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CoveragesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.coverages.<a href="/src/api/resources/preEncounter/resources/coverages/client/Client.ts">get</a>({ ...params }) -> Taiga.PreEncountercoveragesv1Coverage</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

gets a specific Coverage
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.coverages.get({
    id: "id"
});

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

**request:** `Taiga.preEncounter.GetCoveragesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CoveragesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.coverages.<a href="/src/api/resources/preEncounter/resources/coverages/client/Client.ts">getHistory</a>({ ...params }) -> Taiga.PreEncountercoveragesv1Coverage[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets a coverage's history. Full history is returned if no filters are 
defined. The return list is ordered by version, defaulting to ascending.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.coverages.getHistory({
    id: "id"
});

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

**request:** `Taiga.preEncounter.GetHistoryCoveragesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CoveragesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.coverages.<a href="/src/api/resources/preEncounter/resources/coverages/client/Client.ts">scan</a>({ ...params }) -> Taiga.PreEncountercoveragesv1Coverage[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Scans up to 100 coverage updates. The since query parameter is inclusive, and the result list is ordered by updatedAt ascending.

**Polling Pattern:**
To continuously poll for updates without gaps:
1. Make your initial request with a `since` timestamp (e.g., `since=2020-01-01T13:00:00.000Z`)
2. The API returns up to 100 coverage records, sorted by `updated_at` ascending
3. Find the `updated_at` value from the last record in the response
4. Use that `updated_at` value as the `since` parameter in your next request
5. Repeat steps 2-4 to ingest updates until you receive an empty list

**Important Notes:**
- The `since` parameter is inclusive, so you may receive the last record from the previous batch again (you can deduplicate by ID and version)
- All coverage records include `updated_at`, `id`, `version`, `deactivated`, and `updating_user` fields for tracking changes
- Timestamps have millisecond resolution for precise ordering
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.coverages.scan({
    since: "2024-01-15T09:30:00Z"
});

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

**request:** `Taiga.preEncounter.ScanCoveragesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CoveragesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.coverages.<a href="/src/api/resources/preEncounter/resources/coverages/client/Client.ts">batchUpdatePpg</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Finds all coverages associated with the given ppg_id and updates the ppg_fields for each coverage.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.coverages.batchUpdatePpg({
    ppg_id: "ppg_id",
    payer_plan_group_id: "payer_plan_group_id",
    payer_id: "payer_id",
    payer_name: "payer_name",
    plan_type: "09"
});

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

**request:** `Taiga.preEncounter.PreEncountercoveragesv1PayerPlanGroupFields` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CoveragesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.coverages.<a href="/src/api/resources/preEncounter/resources/coverages/client/Client.ts">checkEligibility</a>({ ...params }) -> Taiga.PreEncountereligibilityChecksv1EligibilityCheckMetadata</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Initiates an eligibility check. Returns the metadata of the check if successfully initiated.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.coverages.checkEligibility({
    id: "id",
    service_code: "1",
    date_of_service: "2023-01-15",
    npi: "npi"
});

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

**request:** `Taiga.preEncounter.CheckEligibilityCoveragesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CoveragesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.coverages.<a href="/src/api/resources/preEncounter/resources/coverages/client/Client.ts">getEligibility</a>({ ...params }) -> Taiga.PreEncountercoveragesv1CoverageEligibilityCheckResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets the eligibility of a patient for a specific coverage if successful.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.coverages.getEligibility({
    id: "id",
    check_id: "check_id"
});

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

**request:** `Taiga.preEncounter.GetEligibilityCoveragesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CoveragesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PreEncounter EligibilityChecks
<details><summary><code>client.preEncounter.eligibilityChecks.<a href="/src/api/resources/preEncounter/resources/eligibilityChecks/client/Client.ts">post</a>({ ...params }) -> Taiga.PreEncountereligibilityChecksv1EligibilityCheck</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sends one real-time eligibility check and returns the result in the response. The response has no ID to read the check again later; to save an ID and retrieve the result later without a coverage record, send the check through POST /eligibility-checks/v1/batch.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.eligibilityChecks.post({
    payer_id: "supported-payer-id",
    provider: {
        first_name: "Jane",
        last_name: "Smith",
        npi: "1999999984"
    },
    subscriber: {
        member_id: "EXAMPLE123",
        first_name: "John",
        last_name: "Doe",
        date_of_birth: "1985-05-27"
    },
    encounter: {
        date_of_service: "2026-08-26",
        service_type_codes: ["30"]
    }
});

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

**request:** `Taiga.PreEncountereligibilityChecksv1EligibilityRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EligibilityChecksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.eligibilityChecks.<a href="/src/api/resources/preEncounter/resources/eligibilityChecks/client/Client.ts">batch</a>({ ...params }) -> Taiga.PreEncountereligibilityChecksv1BatchEligibilityResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Queues one or more eligibility checks and returns a `batch_id`. Save it and read the results later with GET /eligibility-checks/v1/batch/{batch_id}; no patient or coverage record is needed. A batch can hold a single check. Set `submitter_transaction_identifier` on each check to match results to your own records.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.eligibilityChecks.batch([{
        submitter_transaction_identifier: "console-check-0001",
        payer_id: "supported-payer-id",
        provider: {
            first_name: "Jane",
            last_name: "Smith",
            npi: "1999999984"
        },
        subscriber: {
            member_id: "EXAMPLE123",
            first_name: "John",
            last_name: "Doe",
            date_of_birth: "1985-05-27"
        },
        encounter: {
            date_of_service: "2026-08-26",
            service_type_codes: ["AL"]
        }
    }]);

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

**request:** `Taiga.PreEncountereligibilityChecksv1EligibilityRequest[]` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EligibilityChecksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.eligibilityChecks.<a href="/src/api/resources/preEncounter/resources/eligibilityChecks/client/Client.ts">pollBatch</a>({ ...params }) -> core.Page&lt;Taiga.PreEncountereligibilityChecksv1EligibilityCheck, Taiga.PreEncountereligibilityChecksv1EligibilityCheckPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns the eligibility checks in a batch your organization created, with no patient or coverage record needed. Batch checks run asynchronously, so read again until the results you need are present. Match each result to your record with `submitter_transaction_identifier`. A `batch_id` your organization did not create returns 404.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.preEncounter.eligibilityChecks.pollBatch({
    batch_id: "batch_id"
});
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.preEncounter.eligibilityChecks.pollBatch({
    batch_id: "batch_id"
});
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.preEncounter.PollBatchEligibilityChecksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EligibilityChecksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.eligibilityChecks.<a href="/src/api/resources/preEncounter/resources/eligibilityChecks/client/Client.ts">payerSearch</a>({ ...params }) -> core.Page&lt;Taiga.PreEncountereligibilityChecksv1StediPayerItem, Taiga.PreEncountereligibilityChecksv1PayerSearchResponse&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Searches the payer directory by name or payer ID. `page_size` must be between 10 and 100 and defaults to 20. Pass `next_page_token` back as `page_token` for the next page. Send a payer's `primary_payer_id` as the `payer_id` on an eligibility check.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.preEncounter.eligibilityChecks.payerSearch();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.preEncounter.eligibilityChecks.payerSearch();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.preEncounter.PayerSearchEligibilityChecksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EligibilityChecksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.eligibilityChecks.<a href="/src/api/resources/preEncounter/resources/eligibilityChecks/client/Client.ts">recommendation</a>({ ...params }) -> Taiga.PreEncountereligibilityChecksv1EligibilityRecommendation[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets recommendation for eligibility checks based on filters. This endpoint will retrieve all the latest eligibility recommendations for each 
eligibility recommendation type for the given filters. If you want to get a specific recommendation type, you can use the `type` query parameter.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.eligibilityChecks.recommendation();

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

**request:** `Taiga.preEncounter.RecommendationEligibilityChecksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EligibilityChecksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.eligibilityChecks.<a href="/src/api/resources/preEncounter/resources/eligibilityChecks/client/Client.ts">voteRecommendation</a>({ ...params }) -> Taiga.PreEncountereligibilityChecksv1EligibilityRecommendation</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Submit user feedback on an eligibility recommendation. The path must contain the next version number to prevent race conditions. For example, if the current version of the recommendation is n, you will need to send a request to this endpoint with `/{recommendation_id}/{n+1}/vote` to update the vote.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.eligibilityChecks.voteRecommendation({
    recommendation_id: "recommendation_id",
    version: "version",
    body: {
        user_id: "user_id",
        value: "UPVOTE"
    }
});

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

**request:** `Taiga.preEncounter.VoteRecommendationEligibilityChecksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EligibilityChecksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.eligibilityChecks.<a href="/src/api/resources/preEncounter/resources/eligibilityChecks/client/Client.ts">insuranceDiscovery</a>({ ...params }) -> Taiga.PreEncountereligibilityChecksv1InsuranceDiscoveryResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sends an insurance discovery check to find potential coverage matches for a patient through Stedi.
Given patient demographics, this endpoint discovers what insurance coverages exist for the patient.
We recommend using the coverages check_insurance_discovery_passthrough API, as it allows long-running discovery requests to complete.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.eligibilityChecks.insuranceDiscovery({
    provider: {
        npi: "npi"
    },
    subscriber: {
        first_name: "first_name",
        last_name: "last_name"
    }
});

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

**request:** `Taiga.preEncounter.PreEncountereligibilityChecksv1InsuranceDiscoveryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EligibilityChecksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.eligibilityChecks.<a href="/src/api/resources/preEncounter/resources/eligibilityChecks/client/Client.ts">coordinationOfBenefits</a>({ ...params }) -> Taiga.PreEncountereligibilityChecksv1CoordinationOfBenefitsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sends a coordination of benefits check through Stedi to determine whether a patient has
coverage overlap across multiple payers and, if so, which payer is primary.
Medicare and Medicare Advantage plans are not supported.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.eligibilityChecks.coordinationOfBenefits({
    trading_partner_service_id: "trading_partner_service_id",
    provider: {
        npi: "npi"
    },
    subscriber: {
        first_name: "first_name",
        last_name: "last_name",
        date_of_birth: "date_of_birth"
    },
    encounter: {}
});

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

**request:** `Taiga.preEncounter.PreEncountereligibilityChecksv1CoordinationOfBenefitsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EligibilityChecksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PreEncounter Images
<details><summary><code>client.preEncounter.images.<a href="/src/api/resources/preEncounter/resources/images/client/Client.ts">list</a>({ ...params }) -> Taiga.PreEncounterimagesv1Image[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Searches for images that match the query parameters.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.images.list();

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

**request:** `Taiga.preEncounter.ListImagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ImagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.images.<a href="/src/api/resources/preEncounter/resources/images/client/Client.ts">create</a>({ ...params }) -> Taiga.PreEncounterimagesv1Image</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Adds an image.  VersionConflictError is returned if a front or back of this coverage already exists.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.images.create({
    file_name: "file_name",
    display_name: "display_name",
    file_type: "file_type",
    status: "PENDING"
});

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

**request:** `Taiga.PreEncounterimagesv1MutableImage` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ImagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.images.<a href="/src/api/resources/preEncounter/resources/images/client/Client.ts">get</a>({ ...params }) -> Taiga.PreEncounterimagesv1Image</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets an image by imageId.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.images.get({
    id: "id"
});

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

**request:** `Taiga.preEncounter.GetImagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ImagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.images.<a href="/src/api/resources/preEncounter/resources/images/client/Client.ts">update</a>({ ...params }) -> Taiga.PreEncounterimagesv1Image</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates an Image. The path must contain the version being written, which is the object's current version plus 1 (a create returns version 0, so the first update uses 1). Sending the current version returns 409 Version conflict. Use this to set status to UPLOADED once the file has been PUT to the signed_url from the create.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.images.update({
    id: "id",
    version: "version",
    body: {
        file_name: "file_name",
        display_name: "display_name",
        file_type: "file_type",
        status: "PENDING"
    }
});

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

**request:** `Taiga.preEncounter.UpdateImagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ImagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.images.<a href="/src/api/resources/preEncounter/resources/images/client/Client.ts">deactivate</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sets an Image as deactivated. The path must contain the version being written, which is the object's current version plus 1 (a create returns version 0, so the first deactivate uses 1). Sending the current version returns 409 Version conflict.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.images.deactivate({
    id: "id",
    version: "version"
});

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

**request:** `Taiga.preEncounter.DeactivateImagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ImagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PreEncounter Lists
<details><summary><code>client.preEncounter.lists.<a href="/src/api/resources/preEncounter/resources/lists/client/Client.ts">getPatientList</a>({ ...params }) -> core.Page&lt;Taiga.PreEncounterlistsv1PatientListItem, Taiga.PreEncounterlistsv1PatientListPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets patients with dependent objects for patients that match the query parameters.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.preEncounter.lists.getPatientList();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.preEncounter.lists.getPatientList();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.preEncounter.GetPatientListListsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ListsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.lists.<a href="/src/api/resources/preEncounter/resources/lists/client/Client.ts">getAppointmentList</a>({ ...params }) -> core.Page&lt;Taiga.PreEncounterlistsv1AppointmentListItem, Taiga.PreEncounterlistsv1AppointmentListPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Searches for appointments that match the query parameters.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.preEncounter.lists.getAppointmentList();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.preEncounter.lists.getAppointmentList();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.preEncounter.GetAppointmentListListsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ListsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PreEncounter Notes
<details><summary><code>client.preEncounter.notes.<a href="/src/api/resources/preEncounter/resources/notes/client/Client.ts">get</a>({ ...params }) -> Taiga.PreEncounternotesv1Note</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets a note by NoteId.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.notes.get({
    id: "id"
});

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

**request:** `Taiga.preEncounter.GetNotesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NotesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.notes.<a href="/src/api/resources/preEncounter/resources/notes/client/Client.ts">create</a>({ ...params }) -> Taiga.PreEncounternotesv1Note</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Adds a new note.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.notes.create({
    value: "value"
});

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

**request:** `Taiga.PreEncounternotesv1MutableNote` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NotesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.notes.<a href="/src/api/resources/preEncounter/resources/notes/client/Client.ts">update</a>({ ...params }) -> Taiga.PreEncounternotesv1Note</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates a note. The path must contain the most recent version to prevent races.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.notes.update({
    id: "id",
    version: "version",
    body: {
        value: "value"
    }
});

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

**request:** `Taiga.preEncounter.UpdateNotesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NotesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.notes.<a href="/src/api/resources/preEncounter/resources/notes/client/Client.ts">deactivate</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sets a note as deactivated.  The path must contain the most recent version to prevent races.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.notes.deactivate({
    id: "id",
    version: "version"
});

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

**request:** `Taiga.preEncounter.DeactivateNotesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `NotesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PreEncounter OrganizationExternalProviders
<details><summary><code>client.preEncounter.organizationExternalProviders.<a href="/src/api/resources/preEncounter/resources/organizationExternalProviders/client/Client.ts">get</a>({ ...params }) -> Taiga.PreEncounterorganizationExternalProvidersv1OrganizationExternalProvider</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets an organization external provider by ID.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.organizationExternalProviders.get({
    id: "id"
});

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

**request:** `Taiga.preEncounter.GetOrganizationExternalProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationExternalProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.organizationExternalProviders.<a href="/src/api/resources/preEncounter/resources/organizationExternalProviders/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.PreEncounterorganizationExternalProvidersv1OrganizationExternalProvider, Taiga.PreEncounterorganizationExternalProvidersv1OrganizationExternalProviderPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Searches for organization external providers that match the query parameters.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.preEncounter.organizationExternalProviders.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.preEncounter.organizationExternalProviders.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.preEncounter.ListOrganizationExternalProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationExternalProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.organizationExternalProviders.<a href="/src/api/resources/preEncounter/resources/organizationExternalProviders/client/Client.ts">create</a>({ ...params }) -> Taiga.PreEncounterorganizationExternalProvidersv1OrganizationExternalProvider</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates a new organization external provider. BadRequestError is returned when the NPI is already in use.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.organizationExternalProviders.create({
    name: {
        family: "family",
        given: ["given"],
        use: "USUAL"
    },
    types: ["REFERRING"]
});

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

**request:** `Taiga.PreEncounterorganizationExternalProvidersv1MutableOrganizationExternalProvider` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationExternalProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.organizationExternalProviders.<a href="/src/api/resources/preEncounter/resources/organizationExternalProviders/client/Client.ts">update</a>({ ...params }) -> Taiga.PreEncounterorganizationExternalProvidersv1OrganizationExternalProvider</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates an organization external provider. The path must contain the next version number to prevent race conditions. For example, if the current version of the provider is n, you will need to send a request to this endpoint with `/{id}/n+1` to update the provider. Updating historic versions is not supported. BadRequestError is returned when the NPI is already in use by another provider.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.organizationExternalProviders.update({
    id: "id",
    version: "version",
    body: {
        name: {
            family: "family",
            given: ["given"],
            use: "USUAL"
        },
        types: ["REFERRING"]
    }
});

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

**request:** `Taiga.preEncounter.UpdateOrganizationExternalProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationExternalProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.organizationExternalProviders.<a href="/src/api/resources/preEncounter/resources/organizationExternalProviders/client/Client.ts">deactivate</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sets an organization external provider as deactivated. The path must contain the most recent version plus 1 to prevent race conditions. Deactivating historic versions is not supported.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.organizationExternalProviders.deactivate({
    id: "id",
    version: "version"
});

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

**request:** `Taiga.preEncounter.DeactivateOrganizationExternalProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationExternalProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.organizationExternalProviders.<a href="/src/api/resources/preEncounter/resources/organizationExternalProviders/client/Client.ts">scan</a>({ ...params }) -> Taiga.PreEncounterorganizationExternalProvidersv1OrganizationExternalProvider[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Scans up to 1000 organization external provider updates. The since query parameter is inclusive, and the result list is ordered by updatedAt ascending.

**Polling Pattern:**
To continuously poll for updates without gaps:
1. Make your initial request with a `since` timestamp (e.g., `since=2020-01-01T13:00:00.000Z`)
2. The API returns 100 by default and up to 1000 records, sorted by `updated_at` ascending
3. Find the `updated_at` value from the last record in the response
4. Use that `updated_at` value as the `since` parameter in your next request
5. Repeat steps 2-4 to ingest updates until you receive an empty list

**Important Notes:**
- The `since` parameter is inclusive, so you may receive the last record from the previous batch again (you can deduplicate by ID and version)
- All records include `updated_at`, `id`, `version`, `deactivated`, and `updating_user` fields for tracking changes
- Timestamps have millisecond resolution for precise ordering
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.organizationExternalProviders.scan({
    since: "2024-01-15T09:30:00Z"
});

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

**request:** `Taiga.preEncounter.ScanOrganizationExternalProvidersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrganizationExternalProvidersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PreEncounter Patients
<details><summary><code>client.preEncounter.patients.<a href="/src/api/resources/preEncounter/resources/patients/client/Client.ts">search</a>({ ...params }) -> Taiga.PreEncounterpatientsv1Patient[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns a list of Patients based on the search criteria.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.patients.search();

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

**request:** `Taiga.preEncounter.SearchPatientsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.patients.<a href="/src/api/resources/preEncounter/resources/patients/client/Client.ts">create</a>({ ...params }) -> Taiga.PreEncounterpatientsv1Patient</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Adds a patient.  VersionConflictError is returned when the patient's external ID is already in use.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.patients.create({
    body: {
        name: {
            family: "family",
            given: ["given"],
            use: "USUAL"
        },
        other_names: [{
                family: "family",
                given: ["given"],
                use: "USUAL"
            }],
        birth_date: "2023-01-15",
        biological_sex: "FEMALE",
        primary_address: {
            use: "HOME",
            line: ["line"],
            city: "city",
            state: "state",
            postal_code: "postal_code",
            country: "country"
        },
        other_addresses: [{
                use: "HOME",
                line: ["line"],
                city: "city",
                state: "state",
                postal_code: "postal_code",
                country: "country"
            }],
        other_telecoms: [{
                value: "value",
                use: "HOME"
            }],
        contacts: [{
                relationship: ["SELF"],
                name: {
                    family: "family",
                    given: ["given"],
                    use: "USUAL"
                },
                telecoms: [{
                        value: "value",
                        use: "HOME"
                    }],
                addresses: [{
                        use: "HOME",
                        line: ["line"],
                        city: "city",
                        state: "state",
                        postal_code: "postal_code",
                        country: "country"
                    }]
            }],
        general_practitioners: [{
                name: {
                    family: "family",
                    given: ["given"],
                    use: "USUAL"
                },
                telecoms: [{
                        value: "value",
                        use: "HOME"
                    }]
            }],
        filing_order: {
            coverages: ["coverages"]
        }
    }
});

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

**request:** `Taiga.preEncounter.CreatePatientsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.patients.<a href="/src/api/resources/preEncounter/resources/patients/client/Client.ts">createWithMrn</a>({ ...params }) -> Taiga.PreEncounterpatientsv1Patient</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Adds a patient and hydrates their MRN with a pre-existing MRN. Once this patient is created their MRN will not be editable. BadRequestError is returned when the MRN is greater than 20 characters. A 409 means the MRN or demographics matched an existing patient: the body carries `data.potentialDuplicates[]` with `existingPatientId` and `existingPatientMrn` for patients in your organization, and an empty list means the identifier is unavailable. Read the current `version` with GET /patients/v1/{id} before a PUT.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.patients.createWithMrn({
    body: {
        name: {
            family: "family",
            given: ["given"],
            use: "USUAL"
        },
        other_names: [{
                family: "family",
                given: ["given"],
                use: "USUAL"
            }],
        birth_date: "2023-01-15",
        biological_sex: "FEMALE",
        primary_address: {
            use: "HOME",
            line: ["line"],
            city: "city",
            state: "state",
            postal_code: "postal_code",
            country: "country"
        },
        other_addresses: [{
                use: "HOME",
                line: ["line"],
                city: "city",
                state: "state",
                postal_code: "postal_code",
                country: "country"
            }],
        other_telecoms: [{
                value: "value",
                use: "HOME"
            }],
        contacts: [{
                relationship: ["SELF"],
                name: {
                    family: "family",
                    given: ["given"],
                    use: "USUAL"
                },
                telecoms: [{
                        value: "value",
                        use: "HOME"
                    }],
                addresses: [{
                        use: "HOME",
                        line: ["line"],
                        city: "city",
                        state: "state",
                        postal_code: "postal_code",
                        country: "country"
                    }]
            }],
        general_practitioners: [{
                name: {
                    family: "family",
                    given: ["given"],
                    use: "USUAL"
                },
                telecoms: [{
                        value: "value",
                        use: "HOME"
                    }]
            }],
        filing_order: {
            coverages: ["coverages"]
        },
        mrn: "mrn"
    }
});

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

**request:** `Taiga.preEncounter.CreateWithMrnPatientsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.patients.<a href="/src/api/resources/preEncounter/resources/patients/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.PreEncounterpatientsv1Patient, Taiga.PreEncounterpatientsv1PatientPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Searches for patients that match the query parameters.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.preEncounter.patients.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.preEncounter.patients.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.preEncounter.ListPatientsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.patients.<a href="/src/api/resources/preEncounter/resources/patients/client/Client.ts">searchProviders</a>({ ...params }) -> Taiga.PreEncounterExternalProvider[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Searches for referring providers that match the query parameters.  The search is case-insensitive, supports fuzzy matching, and matches against provider name and NPI. The search criteria must be an alphanumeric string, and the search is limited to the first 20 results.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.patients.searchProviders({
    search_criteria: "search_criteria"
});

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

**request:** `Taiga.preEncounter.SearchProvidersPatientsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.patients.<a href="/src/api/resources/preEncounter/resources/patients/client/Client.ts">get</a>({ ...params }) -> Taiga.PreEncounterpatientsv1Patient</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets a patient.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.patients.get({
    id: "id"
});

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

**request:** `Taiga.preEncounter.GetPatientsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.patients.<a href="/src/api/resources/preEncounter/resources/patients/client/Client.ts">getByMrn</a>({ ...params }) -> Taiga.PreEncounterpatientsv1Patient</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets a patient by MRN. Returns the patient only when it belongs to the calling organization. Any other MRN, including one that does not exist, returns 404.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.patients.getByMrn({
    mrn: "mrn"
});

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

**request:** `Taiga.preEncounter.GetByMrnPatientsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.patients.<a href="/src/api/resources/preEncounter/resources/patients/client/Client.ts">getHistory</a>({ ...params }) -> Taiga.PreEncounterpatientsv1Patient[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets a patient along with it's full history.  The return list is ordered by version ascending.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.patients.getHistory({
    id: "id"
});

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

**request:** `Taiga.preEncounter.GetHistoryPatientsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.patients.<a href="/src/api/resources/preEncounter/resources/patients/client/Client.ts">getCoverageSnapshot</a>({ ...params }) -> Taiga.PreEncounterpatientsv1PatientCoverageSnapshot</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets a patient along with their coverages at a specific point in time. Note that the date passed in is only used to determine what the filing order was for that patient during that time. The actual data returned will always be the latest version of the patient and coverages.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.patients.getCoverageSnapshot({
    id: "id"
});

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

**request:** `Taiga.preEncounter.GetCoverageSnapshotPatientsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.patients.<a href="/src/api/resources/preEncounter/resources/patients/client/Client.ts">getEligibilityTimeline</a>({ ...params }) -> core.Page&lt;Taiga.PreEncounterpatientsv1EligibilityTimelineEvent, Taiga.PreEncounterpatientsv1EligibilityTimelinePage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets a patient's eligibility audit timeline, newest-first.  Org-scoped and keyset-paginated.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.preEncounter.patients.getEligibilityTimeline({
    id: "id"
});
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.preEncounter.patients.getEligibilityTimeline({
    id: "id"
});
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.preEncounter.GetEligibilityTimelinePatientsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.patients.<a href="/src/api/resources/preEncounter/resources/patients/client/Client.ts">update</a>({ ...params }) -> Taiga.PreEncounterpatientsv1Patient</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates a patient. The path must contain the next version number to prevent race conditions. For example, if the current version of the patient is n, you will need to send a request to this endpoint with `/{id}/n+1` to update the patient. Updating historic versions is not supported. The body is the update shape: `mrn` is fixed at create time and must be omitted; including it returns a validation error.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.patients.update({
    id: "id",
    version: "version",
    body: {
        name: {
            family: "family",
            given: ["given"],
            use: "USUAL"
        },
        other_names: [{
                family: "family",
                given: ["given"],
                use: "USUAL"
            }],
        birth_date: "2023-01-15",
        biological_sex: "FEMALE",
        primary_address: {
            use: "HOME",
            line: ["line"],
            city: "city",
            state: "state",
            postal_code: "postal_code",
            country: "country"
        },
        other_addresses: [{
                use: "HOME",
                line: ["line"],
                city: "city",
                state: "state",
                postal_code: "postal_code",
                country: "country"
            }],
        other_telecoms: [{
                value: "value",
                use: "HOME"
            }],
        contacts: [{
                relationship: ["SELF"],
                name: {
                    family: "family",
                    given: ["given"],
                    use: "USUAL"
                },
                telecoms: [{
                        value: "value",
                        use: "HOME"
                    }],
                addresses: [{
                        use: "HOME",
                        line: ["line"],
                        city: "city",
                        state: "state",
                        postal_code: "postal_code",
                        country: "country"
                    }]
            }],
        general_practitioners: [{
                name: {
                    family: "family",
                    given: ["given"],
                    use: "USUAL"
                },
                telecoms: [{
                        value: "value",
                        use: "HOME"
                    }]
            }],
        filing_order: {
            coverages: ["coverages"]
        }
    }
});

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

**request:** `Taiga.preEncounter.UpdatePatientsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.patients.<a href="/src/api/resources/preEncounter/resources/patients/client/Client.ts">deactivate</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sets a patient as deactivated.  The path must contain the most recent version plus 1 to prevent race conditions.  Deactivating historic versions is not supported.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.patients.deactivate({
    id: "id",
    version: "version"
});

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

**request:** `Taiga.preEncounter.DeactivatePatientsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.patients.<a href="/src/api/resources/preEncounter/resources/patients/client/Client.ts">reactivate</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Removes the deactivated flag for a patient.  The path must contain the most recent version plus 1 to prevent race conditions.  Reactivating historic versions is not supported.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.patients.reactivate({
    id: "id",
    version: "version"
});

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

**request:** `Taiga.preEncounter.ReactivatePatientsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.patients.<a href="/src/api/resources/preEncounter/resources/patients/client/Client.ts">scan</a>({ ...params }) -> Taiga.PreEncounterpatientsv1Patient[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Scans up to 1000 patient updates. The since query parameter is inclusive, and the result list is ordered by updatedAt ascending.

**Polling Pattern:**
To continuously poll for updates without gaps:
1. Make your initial request with a `since` timestamp (e.g., `since=2020-01-01T13:00:00.000Z`)
2. The API returns 100 by default and up to 1000 patient records, sorted by `updated_at` ascending
3. Find the `updated_at` value from the last record in the response
4. Use that `updated_at` value as the `since` parameter in your next request
5. Repeat steps 2-4 to ingest updates until you receive an empty list

**Important Notes:**
- The `since` parameter is inclusive, so you may receive the last record from the previous batch again (you can deduplicate by ID and version)
- All patient records include `updated_at`, `id`, `version`, `deactivated`, and `updating_user` fields for tracking changes
- Timestamps have millisecond resolution for precise ordering
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.patients.scan({
    since: "2024-01-15T09:30:00Z"
});

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

**request:** `Taiga.preEncounter.ScanPatientsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PatientsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PreEncounter Tags
<details><summary><code>client.preEncounter.tags.<a href="/src/api/resources/preEncounter/resources/tags/client/Client.ts">get</a>({ ...params }) -> Taiga.PreEncountertagsv1Tag</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets a tag by TagId.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.tags.get({
    id: "id"
});

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

**request:** `Taiga.preEncounter.GetTagsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TagsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.tags.<a href="/src/api/resources/preEncounter/resources/tags/client/Client.ts">list</a>({ ...params }) -> core.Page&lt;Taiga.PreEncountertagsv1Tag, Taiga.PreEncountertagsv1TagPage&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets all tags. Defaults to page size of 1000.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
const pageableResponse = await client.preEncounter.tags.list();
for await (const item of pageableResponse) {
    console.log(item);
}

// Or you can manually iterate page-by-page
let page = await client.preEncounter.tags.list();
while (page.hasNextPage()) {
    page = await page.getNextPage();
}

// You can also access the underlying response
const response = page.response;

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

**request:** `Taiga.preEncounter.ListTagsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TagsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.tags.<a href="/src/api/resources/preEncounter/resources/tags/client/Client.ts">create</a>({ ...params }) -> Taiga.PreEncountertagsv1Tag</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Adds a new tag if it does not already exist, otherwise, returns the existing tag.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.tags.create({
    value: "value"
});

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

**request:** `Taiga.PreEncountertagsv1MutableTag` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TagsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.tags.<a href="/src/api/resources/preEncounter/resources/tags/client/Client.ts">update</a>({ ...params }) -> Taiga.PreEncountertagsv1Tag</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates a tag. The path must contain the most recent version to prevent races.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.tags.update({
    id: "id",
    version: "version",
    body: {
        value: "value"
    }
});

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

**request:** `Taiga.preEncounter.UpdateTagsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TagsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preEncounter.tags.<a href="/src/api/resources/preEncounter/resources/tags/client/Client.ts">deactivate</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sets a tag as deactivated.  The path must contain the most recent version to prevent races.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preEncounter.tags.deactivate({
    id: "id",
    version: "version"
});

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

**request:** `Taiga.preEncounter.DeactivateTagsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TagsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Views Dynamic
<details><summary><code>client.views.dynamic.<a href="/src/api/resources/views/resources/dynamic/client/Client.ts">resolve</a>({ ...params }) -> Taiga.EncounterSummariesv1EncounterSummaryPage</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Resolves a dynamic view to the EncounterSummaries currently present in this view.
Body parameters can include sorting controls.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.views.dynamic.resolve({
    claim_dynamic_view_id: "claim_dynamic_view_id"
});

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

**request:** `Taiga.views.ResolveDynamicRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DynamicClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

