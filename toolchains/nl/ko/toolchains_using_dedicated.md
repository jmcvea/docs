---

copyright:
  years: 2016

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# {{site.data.keyword.Bluemix_notm}} 데디케이티드의 도구 체인 사용
{: #toolchains-using_dedicated}

마지막 업데이트 날짜: 2016년 9월 13일
{: .last-updated}

매일의 개발, 배치 및 운영 작업이 생산적이도록 도구 체인을 사용할 수 있습니다. 도구 체인을 설정하고 나면 도구 통합을 추가, 삭제 또는 구성하고 도구 체인에 대한 액세스를 관리할 수 있습니다.
{: shortdesc}

## 도구 통합 구성
{: #configuring_a_tool_integration_dedicated}

도구 체인을 작성할 때 도구 통합의 구성을 연기한 경우 **구성** 단추가 해당 타일에 표시됩니다. 도구 체인을 작성할 때 도구 통합을 구성한 경우 구성 설정을 업데이트할 수 있습니다.

1. 대시보드의 **DEVOPS** 탭에서 도구 체인을 클릭하여 도구 통합 페이지를 여십시오. 또는 앱 개요 페이지의 오른쪽 상단에서 **도구 체인 보기**를 클릭하십시오.그런 다음 **도구 통합**을 클릭하십시오.
1. 도구 통합을 처음으로 구성해야 하는 경우 해당 타일에서 **구성**을 클릭하십시오.

  ![구성 단추](images/toolchain_tile_configure.png)

 도구 통합 구성을 완료하면 **통합 저장**을 클릭하십시오.
 
1. 도구 통합 구성을 업데이트해야 하는 경우 해당 타일에서 메뉴를 클릭하여 구성 옵션에 액세스하십시오.

  ![구성 메뉴](images/toolchain_tile_menu.png)
 
 설정 업데이트를 완료하고 나면 **통합 저장**을 클릭하십시오.

## 도구 통합 추가
{: #adding_a_tool_integration_dedicated}

도구 체인의 도구 통합을 추가하고 구성할 수 있습니다.

1. 대시보드의 **DEVOPS** 탭에서 도구 체인을 클릭하여 도구 통합 페이지를 여십시오. 또는 앱 개요 페이지의 오른쪽 상단에서 **도구 체인 보기**를 클릭하십시오.그런 다음 **도구 통합**을 클릭하십시오.
1. 추가할 도구 통합 목록을 보려면 추가 단추(+)를 클릭하십시오.
1. 추가할 도구 통합을 클릭하십시오.
1. 도구 통합을 구성하는 데 필요한 정보를 입력하십시오. 
1. **통합 작성**을 클릭하여 도구 체인에 도구 통합을 추가하십시오.

## 도구 통합 삭제
{: #deleting_a_tool_integration}

도구 체인에서 도구 통합을 삭제하는 경우 삭제를 실행 취소할 수 없습니다. 

1. 대시보드의 **DEVOPS** 탭에서 도구 체인을 클릭하여 도구 통합 페이지를 여십시오. 또는 앱 개요 페이지의 오른쪽 상단에서 **도구 체인 보기**를 클릭하십시오.그런 다음 **도구 통합**을 클릭하십시오.
1. 삭제할 도구 통합의 타일에서 메뉴를 클릭하여 구성 옵션에 액세스하십시오. 
1. 도구 체인에서 도구 통합을 삭제하려면 **삭제**를 클릭하십시오.
1. **삭제**를 클릭하여 확인하십시오. 

## 액세스 관리
{: #managing_access_dedicated}

도구 체인이 연관된 조직(org)에 추가하여 사용자에게 도구 체인에 대한 액세스 권한을 부여할 수 있습니다. 각 도구 체인은 특정 조직과 연관되며 해당 조직의 구성원인 사용자가 연관된 도구 체인에 액세스할 수 있습니다. 현재 작업 중인 조직을 보려면 메뉴 표시줄에서 **{{site.data.keyword.avatar}}** 아이콘 ![아바타 아이콘](../icons/i-avatar-icon.svg)을 클릭하십시오. 다른 도구 체인 세트에 액세스하려면 다른 조직으로 전환하십시오.

{{site.data.keyword.Bluemix}} 조직 및 영역에 사용자를 추가할 때 사용자가 {{site.data.keyword.Bluemix_notm}} ID 및 비밀번호를 사용하여 GitHub Enterprise에 로그인할 수 있습니다. 사용자가 로그인하면 계정이 작성됩니다. {{site.data.keyword.Bluemix_notm}} 조직 및 영역에 사용자를 추가할 때 계정이 GitHub Enterprise 저장소에 자동으로 추가되지 않습니다. 저장소의 관리자 권한이 있는 사용자가 추가해야 합니다. 자세한 정보는 [Dedicated GitHub Enterprise 사용(링크가 새 창에서 열림)](../services/ghededicated/index.html){: new_window}을 참조하십시오.

사용자를 추가하려면 다음 단계를 따르십시오. 

1. 대시보드의 **DEVOPS** 탭에서 도구 체인을 클릭하여 도구 통합 페이지를 여십시오. 그런 다음 **관리**를 클릭하십시오. 또는 앱 개요 페이지의 오른쪽 상단에서 **도구 체인 보기**를 클릭하십시오.그런 다음 **관리**를 클릭하십시오.   
1. 조직에 대한 링크를 클릭하십시오. 
1. 조직 관리 페이지에서 **사용자 초대**를 클릭하고 사용자 이메일 주소를 입력하십시오.
1. {{site.data.keyword.Bluemix_notm}} 조직의 사용자를 관리할 고급 권한을 제공하려면 하나 이상의 **관리자**, **비용 청구 관리자** 또는 **감사자** 선택란을 선택하십시오.
1. **초대**를 클릭하십시오.
1. **저장**을 클릭하십시오. 

## 도구 체인 삭제
{: #deleting_a_toolchain_dedicated}

도구 체인을 삭제하고 삭제할 연관된 도구 통합을 지정할 수 있습니다. 도구 체인을 삭제하면 삭제를 실행 취소할 수 없습니다.

1. 대시보드의 **DEVOPS** 탭에서 도구 체인을 클릭하여 도구 통합 페이지를 여십시오. 그런 다음 **관리**를 클릭하십시오. 또는 앱 개요 페이지의 오른쪽 상단에서 **도구 체인 보기**를 클릭하십시오.그런 다음 **관리**를 클릭하십시오. 
1. **도구 체인 삭제**를 클릭하고 삭제할 도구 통합을 검토하거나 조정하십시오.
1. 도구 체인의 이름을 입력하고 **삭제**를 클릭하여 삭제를 확인하십시오.

 **팁**: GitHub Enterprise 도구 통합을 삭제해도 연관된 GitHub Enterprise 저장소는 GitHub Enterprise에서 삭제되지 않습니다. GitHub Enterprise에서 수동으로 저장소를 제거해야 합니다.
