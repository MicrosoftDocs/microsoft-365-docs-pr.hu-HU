---
title: Appvédelmi beállítások megadása androidos vagy iOS-es eszközökhöz
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- Adm_O365
- Core_O365Admin_Migration
- MiniMaven
- MSB365
search.appverid:
- BCS160
- MET150
ms.assetid: 6f2b80b4-81c3-4714-a7bc-ae69313e8a33
description: Útmutató létrehozása, szerkesztése, vagy app kezelési házirend törlése és Android vagy iOS eszközökön Munkafájlok védelme.
ms.openlocfilehash: ed03227496120369b94bf2396974eebfd7798678
ms.sourcegitcommit: e491c4713115610cbe13d2fbd0d65e1a41c34d62
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 01/16/2019
ms.locfileid: "26983665"
---
# <a name="set-app-protection-settings-for-android-or-ios-devices"></a><span data-ttu-id="63806-103">Appvédelmi beállítások megadása androidos vagy iOS-es eszközökhöz</span><span class="sxs-lookup"><span data-stu-id="63806-103">Set app protection settings for Android or iOS devices</span></span>

## <a name="create-an-app-management-policy"></a><span data-ttu-id="63806-104">Appkezelési házirend létrehozása</span><span class="sxs-lookup"><span data-stu-id="63806-104">Create an app management policy</span></span>

1. <span data-ttu-id="63806-105">Jelentkezzen be a [Microsoft 365 Business](https://portal.office.com) szolgáltatásba globális rendszergazdai hitelesítő adatokkal.</span><span class="sxs-lookup"><span data-stu-id="63806-105">Sign in to [Microsoft 365 Business](https://portal.office.com) with global admin credentials.</span></span> 
    
2. <span data-ttu-id="63806-106">A felügyeleti központ **Eszközházirendek** kártyáján válassza a **Házirend felvétele** lehetőséget.</span><span class="sxs-lookup"><span data-stu-id="63806-106">In the admin center, on the **Device policies** card, choose **Add policy**.</span></span>
    
    ![Device policies card in the admin center.](media/27c12b61-d112-4348-b557-4f3e46204797.png)
  
3. <span data-ttu-id="63806-108">A **Házirend felvétele** ablaktáblában adja meg a házirend egyedi nevét.</span><span class="sxs-lookup"><span data-stu-id="63806-108">On the **Add policy** pane, enter a unique name for this policy.</span></span> 
    
4. <span data-ttu-id="63806-109">A **Házirend típusa** csoportban válassza az **Alkalmazáskezelés Android-eszközökhöz** vagy az **Alkalmazáskezelés iOS-eszközökhöz** lehetőséget attól függően, hogy milyen házirendkészletet szeretne létrehozni.</span><span class="sxs-lookup"><span data-stu-id="63806-109">Under **Policy type**, choose **Application Management for Android** or **Application Management for iOS** depending on which set of policies you want to create.</span></span> 
    
5. <span data-ttu-id="63806-p101">Bontsa ki a **védelem Munkafájlok, ha az eszköz elveszett vagy ellopott** és **kezelése, hogy a felhasználók miként férhetnek hozzá a mobil eszközökön található Office-fájlok** \> hogyan szeretné a beállításokat. Alapértelmezés szerint nincs **bekapcsolva** **kezelése, hogy a felhasználók miként férhetnek hozzá a mobil eszközökön található Office-fájlokat** , de javasoljuk, hogy kapcsolja **be** , és elfogadhatja az alapértelmezett értékeket. További tudnivalókért tanulmányozza a [rendelkezésre álló beállításokat](app-protection-settings-for-android-and-ios.md#bkmk_availablesettings) .</span><span class="sxs-lookup"><span data-stu-id="63806-p101">Expand **Protect work files when devices are lost or stolen** and **Manage how users access Office files on mobile devices** \> configure the settings how you would like. The **Manage how users access Office files on mobile devices** is **Off** by default, but it is recommended that you turn it **On** and accept the default values. See [Available settings](app-protection-settings-for-android-and-ios.md#bkmk_availablesettings) for more information.</span></span> 
    
    <span data-ttu-id="63806-113">Az **Alapértelmezett beállítások visszaállítása** hivatkozásra kattintva bármikor visszatérhet az alapértelmezett beállításokhoz.</span><span class="sxs-lookup"><span data-stu-id="63806-113">You can always use the **Reset default settings** link to return to the default setting.</span></span> 
    
    ![Screenshot of Create a policy with Application management for Android selected](media/eabbe06d-ac0a-4f3a-8630-68c808b1e662.png)
  
6. <span data-ttu-id="63806-p102">Ezután döntse el, **fog kapni, akik ezeket a beállításokat?** Ha nem szeretné az alapértelmezett **Felhasználók** biztonsági csoporthoz, választhat **módosítása**, a biztonsági csoportok, akik ezeket a beállításokat kap \> **kiválasztása**.</span><span class="sxs-lookup"><span data-stu-id="63806-p102">Next decide **Who will get these settings?** If you don't want to use the default **All Users** security group, choose **Change**, choose the security groups who will get these settings \> **Select**.</span></span>
    
7. <span data-ttu-id="63806-117">Végül válassza a **Kész** lehetőséget a házirend mentéséhez és eszközökhöz való hozzárendeléséhez.</span><span class="sxs-lookup"><span data-stu-id="63806-117">Finally, choose **Done** to save the policy, and assign it to devices.</span></span> 
    
## <a name="edit-an-app-management-policy"></a><span data-ttu-id="63806-118">Appkezelési házirend szerkesztése</span><span class="sxs-lookup"><span data-stu-id="63806-118">Edit an app management policy</span></span>

1. <span data-ttu-id="63806-119">A **házirendek** kartonon válassza a **házirend szerkesztése**.</span><span class="sxs-lookup"><span data-stu-id="63806-119">On the **Policies** card, choose **Edit policy**.</span></span>
    
2. <span data-ttu-id="63806-120">A **Házirend szerkesztése** ablaktáblában válassza ki a módosítani kívánt házirendet.</span><span class="sxs-lookup"><span data-stu-id="63806-120">On the **Edit policy** pane, choose the policy you want to change</span></span> 
    
3. <span data-ttu-id="63806-p103">Válassza a **Szerkesztés** elemet az egyes beállítások mellett a házirend értékeinek módosításához. Amikor módosít egy értéket, azt a rendszer automatikusan menti a házirendben.</span><span class="sxs-lookup"><span data-stu-id="63806-p103">Choose **Edit** next to each setting to change the values in the policy. When you change a value, it is automatically saved into the policy</span></span> 
    
4. <span data-ttu-id="63806-123">Ha végzett, zárja be a **Házirend szerkesztése** ablaktáblát.</span><span class="sxs-lookup"><span data-stu-id="63806-123">When you are finished, close the **Edit policy** pane.</span></span> 
    
## <a name="delete-an-app-management-policy"></a><span data-ttu-id="63806-124">Appkezelési házirend törlése</span><span class="sxs-lookup"><span data-stu-id="63806-124">Delete an app management policy</span></span>

1. <span data-ttu-id="63806-125">A **Házirendek** kártyán válassza a **Házirend törlése** elemet.</span><span class="sxs-lookup"><span data-stu-id="63806-125">On the **Policies** card, choose **Delete policy**.</span></span>
    
2. <span data-ttu-id="63806-126">**Házirend törlése** ablakban válassza ki a törölni kívánt házirendek \> **Jelölje ki**, majd **megerősítése** a házirend vagy a választott házirendek törlése.</span><span class="sxs-lookup"><span data-stu-id="63806-126">On the **Delete policy** pane, choose the policies you want to delete \> **Select**, then **Confirm** to delete the policy or policies you chose.</span></span> 
    
## <a name="available-settings"></a><span data-ttu-id="63806-127">Rendelkezésre álló beállítások</span><span class="sxs-lookup"><span data-stu-id="63806-127">Available settings</span></span>

<span data-ttu-id="63806-128">Az alábbi táblázatok részletes információkkal szolgálnak azokról a beállításokról, amelyekkel védelmet nyújthat az eszközökön lévő fájloknak, valamint azokról is, amelyekkel szabályozhatja, hogy a felhasználók hogyan férhessenek hozzá az Office-fájlokhoz mobileszközükről.</span><span class="sxs-lookup"><span data-stu-id="63806-128">The following tables give detailed information about the available settings to protect work files on devices and the settings that control how users access Office files from their mobile devices.</span></span>
  
 <span data-ttu-id="63806-129">További információt [A Microsoft 365 Vállalati verzió védelmi funkcióinak megfelelő Intune-beállítások](map-protection-features-to-intune-settings.md) című témakör tartalmaz.</span><span class="sxs-lookup"><span data-stu-id="63806-129">See [How do protection features in Microsoft 365 Business map to Intune settings](map-protection-features-to-intune-settings.md) for more information.</span></span> 
  
### <a name="settings-that-protect-work-files"></a><span data-ttu-id="63806-130">Munkahelyi fájlok védelmére szolgáló beállítások</span><span class="sxs-lookup"><span data-stu-id="63806-130">Settings that protect work files</span></span>

<span data-ttu-id="63806-131">Az alábbi beállításokkal védhetők meg a munkahelyi fájlok, ha az eszköz elveszett vagy ellopták:</span><span class="sxs-lookup"><span data-stu-id="63806-131">The following settings are available to protect work files if a user's device is lost or stolen:</span></span>
  
|||
|:-----|:-----|
|<span data-ttu-id="63806-132">Beállítás</span><span class="sxs-lookup"><span data-stu-id="63806-132">Setting</span></span>  <br/> |<span data-ttu-id="63806-133">Leírás</span><span class="sxs-lookup"><span data-stu-id="63806-133">Description</span></span>  <br/> |
|<span data-ttu-id="63806-134">Munkahelyi fájlok törlése az inaktív eszközökről ennyi nap után</span><span class="sxs-lookup"><span data-stu-id="63806-134">Delete work files from an inactive device after this many days</span></span>  <br/> |<span data-ttu-id="63806-135">Ha az eszközt az itt megadott számú napig nem használják, akkor a rajta tárolt összes munkahelyi fájl automatikusan törlődik.</span><span class="sxs-lookup"><span data-stu-id="63806-135">If a device is not used for the number of days that you specify here, any work files stored on the device will automatically be deleted.</span></span>  <br/> |
|<span data-ttu-id="63806-136">A felhasználók kényszerítése arra, hogy az összes munkahelyi fájljukat ide mentsék: OneDrive Vállalati verzió</span><span class="sxs-lookup"><span data-stu-id="63806-136">Force users to save all work files to OneDrive for Business</span></span>  <br/> |<span data-ttu-id="63806-137">Ha ez a beállítás **Be** állapotban van, akkor a munkahelyi fájlok mentési helye kizárólag a OneDrive Vállalati verzió lehet.</span><span class="sxs-lookup"><span data-stu-id="63806-137">If this setting is **On**, the only available save location for work files will be OneDrive for Business.</span></span>  <br/> |
|<span data-ttu-id="63806-138">Munkahelyi fájlok titkosítása</span><span class="sxs-lookup"><span data-stu-id="63806-138">Encrypt work files</span></span>  <br/> |<span data-ttu-id="63806-p104">A munkahelyi fájlok titkosítással való védelméhez ezt a beállítást tartsa **Be** állapotban. A céges adatait még az eszköz elvesztése vagy ellopása esetén sem fogja tudni senki olvasni.  </span><span class="sxs-lookup"><span data-stu-id="63806-p104">Keep this setting **On** so that work files are protected by encryption. Even if the device is lost or stolen, no one will be able to read your company data.  </span></span><br/> |
   
### <a name="settings-that-control-how-users-access-office-files-on-mobile-devices"></a><span data-ttu-id="63806-141">Az Office-fájlok mobileszközökön való elérését szabályozó beállítások</span><span class="sxs-lookup"><span data-stu-id="63806-141">Settings that control how users access Office files on mobile devices</span></span>

<span data-ttu-id="63806-142">Az alábbi beállítások használhatók a munkahelyi Office-fájlok elérésének kezelésére:</span><span class="sxs-lookup"><span data-stu-id="63806-142">The following settings are available to manage how users access Office work files:</span></span>
  
|||
|:-----|:-----|
|<span data-ttu-id="63806-143">Beállítás</span><span class="sxs-lookup"><span data-stu-id="63806-143">Setting</span></span>  <br/> |<span data-ttu-id="63806-144">Leírás</span><span class="sxs-lookup"><span data-stu-id="63806-144">Description</span></span>  <br/> |
|<span data-ttu-id="63806-145">PIN-kód vagy ujjlenyomat megkövetelése az Office-appok eléréséhez</span><span class="sxs-lookup"><span data-stu-id="63806-145">Require a PIN or fingerprint to access Office apps</span></span>  <br/> |<span data-ttu-id="63806-146">Ha ez a beállítás **Be** állapotban van, a mobileszközön lévő Office-appok használatához a felhasználónéven és a jelszón kívül a felhasználóknak további hitelesítési módszert is használniuk kell.</span><span class="sxs-lookup"><span data-stu-id="63806-146">If this settings is **On** users have to provide another form of authentication, in addition to their username and password, before they can use Office apps on their mobile device.</span></span>  <br/> |
|<span data-ttu-id="63806-147">PIN-kód visszaállítása ennyi sikertelen bejelentkezési kísérlet után</span><span class="sxs-lookup"><span data-stu-id="63806-147">Reset PIN when login fails this many times</span></span>  <br/> |<span data-ttu-id="63806-148">Annak érdekében, hogy ne lehessen a PIN-kódot véletlenszerű próbálkozásokkal megfejteni, az Ön által megadott számú téves próbálkozás után a PIN-kód alaphelyzetbe áll.</span><span class="sxs-lookup"><span data-stu-id="63806-148">To prevent an unauthorized user from randomly guessing a PIN, the PIN will reset after the number of wrong entries that you specify.</span></span>  <br/> |
|<span data-ttu-id="63806-149">A felhasználónak ismét be kell jelentkeznie az Office-appok ennyi ideig tartó üresjárata után</span><span class="sxs-lookup"><span data-stu-id="63806-149">Require users to sign in again after Office apps have been idle for</span></span>  <br/> |<span data-ttu-id="63806-150">Ezzel a beállítással azt határozhatja meg, hogy a felhasználó mennyi ideig maradhat inaktív, mielőtt újra be kellene jelentkeznie.</span><span class="sxs-lookup"><span data-stu-id="63806-150">This setting determines how long a user can be idle before they are prompted to sign in again.</span></span>  <br/> |
|<span data-ttu-id="63806-151">Hozzáférés letiltása a munkahelyi fájlokhoz a feltört vagy rootolással feltört eszközökön</span><span class="sxs-lookup"><span data-stu-id="63806-151">Deny access to work files on jailbroken or rooted devices</span></span>  <br/> |<span data-ttu-id="63806-p105">A hozzáértő felhasználók esetleg feltört vagy rootolással feltört eszközzel is rendelkezhetnek. Ez azt jelenti, hogy a felhasználó képes módosítani az operációs rendszert, ami sebezhetőbbé teheti az eszközt a kártevőkkel szemben. Ha ez a beállítás **Be** állapotban van, az ilyen eszközök le lesznek tiltva.  </span><span class="sxs-lookup"><span data-stu-id="63806-p105">Clever users may have a device that is jailbroken or rooted. This means that the user can modify the operating system, which can make the device more subject to malware. These devices are blocked when this setting is **On**.  </span></span><br/> |
|<span data-ttu-id="63806-155">A felhasználók másolhatnak tartalmakat az Office-appokból személyes appokba</span><span class="sxs-lookup"><span data-stu-id="63806-155">Allow users to copy content from Office apps into personal apps</span></span>  <br/> |<span data-ttu-id="63806-p106">Azt alapértelmezés szerint engedélyezi, de ha a beállítás be **kapcsolva**, a felhasználó tudta átmásolni információk munkafájlt a személyes fájlok. Ha a beállítás ki **kapcsolva**, a felhasználói információ másolása egy munka fiókból személyes app vagy személyes fiók nem lesz.</span><span class="sxs-lookup"><span data-stu-id="63806-p106">We do allow this by default, but if the setting is **On**, the user could copy information in a work file to a personal file. If the setting is **Off**, the user will be unable to copy information from a work account into a personal app or personal account.  </span></span><br/> |
   

  
