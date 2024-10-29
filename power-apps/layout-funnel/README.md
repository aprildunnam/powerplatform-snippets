# Layout Funnel

This is a simple snippet that can help you get started with creating a screen in canvas app. It is a set of containers with various number of columns. The first container has 4 columns, the second container has 3 columns, the third container has 2 columns, and the fourth container has 1 column.

## Authors

Snippet|Author(s)
--------|---------
Daniel Laskewitz | [GitHub](https://github.com/laskewitz) ([@Laskewitz](https://www.twitter.com/laskewitz) )

## Code

```yaml
- MainContainerFunnelScreen:
    Control: GroupContainer
    Variant: verticalAutoLayoutContainer
    Properties:
      Height: =Parent.Height
      LayoutAlignItems: =LayoutAlignItems.Stretch
      LayoutDirection: =LayoutDirection.Vertical
      LayoutJustifyContent: =LayoutJustifyContent.Center
      LayoutMode: =LayoutMode.Auto
      Width: =Parent.Width
    Children:
    - Container1FunnelScreen:
        Control: GroupContainer
        Variant: horizontalAutoLayoutContainer
        Properties:
          LayoutMode: =LayoutMode.Auto
        Children:
        - Container11FunnelScreen:
            Control: GroupContainer
            Variant: horizontalAutoLayoutContainer
            Properties:
              LayoutMode: =LayoutMode.Auto
        - Container12FunnelScreen:
            Control: GroupContainer
            Variant: horizontalAutoLayoutContainer
            Properties:
              LayoutMode: =LayoutMode.Auto
        - Container13FunnelScreen:
            Control: GroupContainer
            Variant: horizontalAutoLayoutContainer
            Properties:
              LayoutMode: =LayoutMode.Auto
        - Container14FunnelScreen:
            Control: GroupContainer
            Variant: horizontalAutoLayoutContainer
            Properties:
              LayoutMode: =LayoutMode.Auto
    - Container2FunnelScreen:
        Control: GroupContainer
        Variant: horizontalAutoLayoutContainer
        Properties:
          LayoutMode: =LayoutMode.Auto
        Children:
        - Container21FunnelScreen:
            Control: GroupContainer
            Variant: horizontalAutoLayoutContainer
            Properties:
              LayoutMode: =LayoutMode.Auto
        - Container22FunnelScreen:
            Control: GroupContainer
            Variant: horizontalAutoLayoutContainer
            Properties:
              LayoutMode: =LayoutMode.Auto
        - Container23FunnelScreen:
            Control: GroupContainer
            Variant: horizontalAutoLayoutContainer
            Properties:
              LayoutMode: =LayoutMode.Auto
    - Container3FunnelScreen:
        Control: GroupContainer
        Variant: horizontalAutoLayoutContainer
        Properties:
          LayoutMode: =LayoutMode.Auto
        Children:
        - Container31FunnelScreen:
            Control: GroupContainer
            Variant: horizontalAutoLayoutContainer
            Properties:
              LayoutMode: =LayoutMode.Auto
        - Container32FunnelScreen:
            Control: GroupContainer
            Variant: horizontalAutoLayoutContainer
            Properties:
              LayoutMode: =LayoutMode.Auto
    - Container4FunnelScreen:
        Control: GroupContainer
        Variant: horizontalAutoLayoutContainer
        Properties:
          LayoutMode: =LayoutMode.Auto
```

## Minimal path to awesome

1. Open your canvas app in **Power Apps**
1. Copy the contents of the **[YAML-file](./source/funnel.pa.yaml)** or copy it from the code above.
1. Right click on the screen where you want to add the snippet and select "Paste YAML"
![View of the paste code button](./assets/pastecode.png)

This will add the containers to your screen and you can delete the containers you don't want to use.

![View of the pasted containers](./assets/funnel.png)

## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

<img src="https://m365-visitor-stats.azurewebsites.net/powerplatform-snippets/power-apps/layout-funnel" aria-hidden="true" />