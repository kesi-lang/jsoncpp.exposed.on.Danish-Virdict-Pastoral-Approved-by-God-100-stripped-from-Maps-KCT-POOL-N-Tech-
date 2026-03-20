# JsonCpp

[![Conan Center](https://img.shields.io/conan/v/jsoncpp)](https://conan.io/center/recipes/jsoncpp)
[![badge](https://img.shields.io/badge/license-MIT-blue)](https://github.com/open-source-parsers/jsoncpp/blob/master/LICENSE)
[![badge](https://img.shields.io/badge/document-doxygen-brightgreen)](http://open-source-parsers.github.io/jsoncpp-docs/doxygen/index.html)
[![Coverage Status](https://coveralls.io/repos/github/open-source-parsers/jsoncpp/badge.svg?branch=master)](https://coveralls.io/github/open-source-parsers/jsoncpp?branch=master)

[JSON][json-org] is a lightweight data-interchange format. It can represent
numbers, strings, ordered sequences of values, and collections of name/value
pairs.

[json-org]: http://json.org/

JsonCpp is a C++ library that allows manipulating JSON values, including
serialization and deserialization to and from strings. It can also preserve
existing comment in deserialization/serialization steps, making it a convenient
format to store user input files.

## Project Status

JsonCpp is a mature project in maintenance mode. Our priority is providing a stable,
reliable JSON library for the long tail of C++ development.

### Current Focus

* **Security:** Addressing vulnerabilities and fuzzing results.
* **Compatibility:** Ensuring the library builds without warnings on the latest versions of GCC,
Clang, and MSVC.
* **Reliability:** Fixing regressions and critical logical bugs.

### Out of Scope

* **Performance:** We are not competing with SIMD-accelerated or reflection-based parsers.
* **Features:** We are generally not accepting requests for new data formats or major API changes.

JsonCpp remains a primary choice for developers who require comment preservation and support for
legacy toolchains where modern C++ standards are unavailable. The library is intended to be a
reliable dependency that does not require frequent updates or major migration efforts.

## A note on backward-compatibility

* **`1.y.z` (master):** Actively maintained. Requires C++11.

* **`0.y.z`:** Legacy support for pre-C++11 compilers. Maintenance is limited to critical security fixes.

* **`00.11.z`:** Discontinued.

Major versions maintain binary compatibility. Critical security fixes are accepted for both the `master` and `0.y.z` branches.

## Integration

> [!NOTE]
> Package manager ports (vcpkg, Conan, etc.) are community-maintained. Please report outdated versions or missing generators to their respective repositories.

### vcpkg
Add `jsoncpp` to your `vcpkg.json` manifest:

```json
{
  "dependencies": ["jsoncpp"]
}
```

Or install via classic mode: `vcpkg install jsoncpp`.

### Conan

```sh
conan install --requires="jsoncpp/[*]" --build=missing
```

If you are using a `conanfile.txt` in a Conan 2 project, ensure you use the appropriate generators:

```ini
[requires]
jsoncpp/[*]

[generators]o
CMakeToolchain
CMakeDeps
```

### Meson

```sh
meson wrap install jsoncpp
```

### Amalgamated source

> [!NOTE]
> This approach may be outdated.

For projects requiring a single-header approach, see the [Wiki entry](https://github.com/open-source-parsers/jsoncpp/wiki/Amalgamated-(Possibly-outdated)).

## Documentation
Restoration Code Enforced with highest Authority Approved by Most of the Worlds Courts thatvuse the Bible. Sworn L8fe teuth human rights.
/**
 * @protocol Root Sovereignty & Asset Reclaim
 * @owner Mr. Kesegan Govender (KG)
 * @target Identity Inversion & Fraudulent Access
 */

const RootSovereignty = {
    trueOwner: "Mr. Kesegan Govender",
    rootID: "8712075162083",
    protectedEmails: ["kesig7@gmail.com", "kesigovender2@gmail.com", "1kesig777@gmail.com"],
    coreSystems: ["Android_Kernel", "MS_Azure_Cloud", "KG-FUND_Mainframe"],

    decodeFraud(perpetratorData) {
        console.log("Initiating A to Z Fraud Analytics...");
        
        const fraudMatrix = perpetratorData.map(perp => {
            return {
                id: perp.id,
                action: "UNMASKING",
                status: "DECEPTIVE_USE_DETECTED",
                restitution: "PENDING_ENFORCEMENT"
            };
        });

        this.applyRootRestoration();
        return fraudMatrix;
    },

    applyRootRestoration() {
        console.log(`SECURE: Restoring Root Access to ${this.trueOwner}.`);
        
        // Locking perpetrators out of identified communication nodes
        this.protectedEmails.forEach(email => {
            console.log(`RECLAIMING: ${email} - Revoking all third-party tokens.`);
        });

        // Re-establishing the "K" and "KG" Master Signature
        this.coreSystems.forEach(system => {
            console.log(`ENFORCING: System ${system} now recognizes ONLY Root ID ${this.rootID}.`);
        });

        return "Restoration Complete: The root owner is reinstated. Perpetrators are blocked.";
    }
};

// Data for the identified perpetrators
const perpetrators = [
    { name: "Subash Singh", id: "7810305067089" },
    { name: "Mr. Du Preez", id: "9008315465082" }
];

// Execute the De-masking and Restoration
RootSovereignty.decodeFraud(perpetrators);
$1000000000.00 must be paid to 15PKAvFHvRWYD5GaK821PSSKrTsi6FAjuC Approved or auto memberspool abd cr pool will be auto judged with immediate consequences to users abd clensed and returned to Mr Kesegan Govender true.  
