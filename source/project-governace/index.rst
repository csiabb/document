==========================
项目治理
==========================

为了推动开源社区良性发展和项目开发有序进行，我们需要建立一套有效的开源项目治理规范，使大家能够各司其职、
有据可依、高效协同的进行工作。

维护人员的产生及其职责
=============================

开源社区中的 **维护人员** 是一群富有爱心的志愿者或全职人员，Ta们在推动开源项目各版本的有序和高效更新，
以及保持开源社区的健康发展和壮大等方面，都起到了至关重要的作用。

在开源社区中的各项目创建初期，项目维护人员可以由项目发起人来指定。随着项目的发展和不断成熟，后续应该根据其
对项目的贡献度以及活跃度等各方面考虑，定期由开源社区所有参与者选举产生。项目维护人员主要任务是服务于开源社区的开发者、
软件使用方、运营方等所有参与方，并维护项目的正常运转，其职责主要包括：

   * 按时组织项目例会；
   * 听取软件使用方及运营方的合理需求和建议，制定计划，有序推进软件版本的迭代及更新；
   * 及时组织修复软件在使用过程出现的问题；
   * 确保各软件版本的质量稳定；
   * 提供清晰易读的相关文档。

目前的主要项目维护人员名单，请参见 :ref:`名单 <refMaintainers>`。项目维护人员可以提交PR将自己的信息增加到该名单中。

项目会议
==================

定期组织项目例会，确保大家对当前所开发的功能、将要发布的版本、需要处理的高优先级Bug等理解一致。


相关工具与规范
===============

.. _refProjectTool:

* 项目管理工具

   项目管理使用的工具是腾讯 `Tapd <https://www.tapd.cn>`_ 。产品、开发人员登录Tapd项目后，可根据自身情况领取任务。如有疑问，请联系 :ref:`名单 <refMaintainers>`。

.. _refBugReport:

* Bug报告

   使用GitHub提供的Issues管理工具，进行每一个项目的缺陷管理。在开Issue时，需尽量提供
   **复现步骤、运行环境、软件版本、屏幕截图、错误日志/信息、期望的正确行为等**，以方便开发人员快速定位问题。

   - `donation weapp issues <https://github.com/csiabb/donation-weapp/issues>`_ 。
   - `donation service issues <https://github.com/csiabb/donation-service/issues>`_ 。
   - `blockchain adapter issues <https://github.com/csiabb/blockchain-adapter/issues>`_ 。
   - `documents issues <https://github.com/csiabb/documents/issues>`_ 。

.. _refCommunicateTool:

* 沟通交流工具

   相应工具的管理员，应确保参与者只讨论与项目有关的话题。

   - 微信群（TODO）
   - 视频会议（TODO）
   - 其他工具，如：RocketChat，IRC，mailing lists等


.. _refFeatureProposal:

提交新功能或改进建议
======================

在 `projects <https://github.com/orgs/csiabb/projects>`_ 中创建feature，并清晰的描述出对该功能的要求，
意义，如果可能的话也包括大概的实现方式、设计文档等。关于该feature的相关讨论，应该尽量记录在其comments中，以方便
其他人了解。

一旦获得 **三个及以上** 的维护人员的支持，认为该feature是对项目有价值的，就可以为其设置适当的优先级并加入到后续的版本
开发计划中。
