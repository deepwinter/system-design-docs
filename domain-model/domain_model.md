# Domain Model 

<span style="text-decoration:underline;">Treetracker Domain Entities</span>



*   **Capture**: The data that shows something happened (this is the actual proof, impact proof)
*   **Impact Token**: A reference to the capture that can be moved between wallets
    *   (**Relative Impact Value** - property of **Impact Token**, computes relative value based on **Capture** data) 
*   **Wallet**: A container that holds tokens and allows them to be exchanged with other parties
    *   **Impact Wallet Map** - shows trees that have been supported by the holder of a given wallet.
*   **Impact Asset**:  (an entity with social and ecological value)
    *   Aggregate Impact Asset: when a **_conservation entity_** has multiple** impact tokens** attached to it
    *   Fundamental Impact Asset: Synonym for **Impact Token**
*   **Tree:** The main impact asset that Treetracker tracks.
*   **Impact Producer:**: An organization that is coordinating physical responsibility for the growth of the tree.
*   **Impact Manager**: An organization that is coordinating physical responsibility for the growth of the tree.
    *   Responsible for **Impact Manager Map**: her map with all the trees within her project (org map)
    *   **Impact Manager Map**: Permanently shows all **Trees** that an **Impact Manager** has or is coordinating.
*   **Relative Impact Value Matrix**
    *   A table of criteria that computes a relative impact value.  
    *   Version updates released annually
        *   All RIV criteria additions are held for next annual update
*   **Relative Impact Value** **(RIV)**: A value that is comparable between impact tokens, a sum of the values ascribed to all impact factors relevant to this token. 
    *   **Intrinsic Impact Value (IIV)**: The portion of the RIV that comes from the data within or tagged to a **Capture** of an **Impact Asset**. Calculated as a sum of impact values in a matrix, available for each month since the last **Capture**.
    *   **Social Impact Value (SIV)**: The portion of the RIV that comes from direct benefit to the ground operator who produces a **Capture** using our platform.  Probably a discrete value.
    *   **Activity Impact Value (AIV)**: A value we assign based on our idea of the relationship that different types of conservation activities have on _outcomes_ for **Impact Assets**
        *   Assigned value for each monitoring/ update visit (1)
        *   Scaled assigned value for the initial planting (3)

Useful Explanatory Terms



*   An **_impact asset_** is when a **_conservation entity_** has multiple tokens attached to it
    *   **Tree** is our currently supported **_conservation entity_**
    *   An **_impact share_** is one of the multiple **_impact tokens_** attached to a tree
*   **_tree proof / proof of planting_**
    *   Trees interest corporate offset markets (ex. CSR investors) 
        *   **_Tree Proofs_ **- held in the web map & traded 
        *   Proofs of Planting - interchangeable language with _Tree Proofs_
    *   Impact tokens for everyday consumer markets (ex. Sustainably run app)
        *   Do not trade_ trees_ in wallet API
        *   Greenstand sells the_ planting of a tree _
