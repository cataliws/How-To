# Offers

Offers are the products or services you sell through your website.

To create and manage offers, click the **Offers** link in the sidebar of your dashboard or visit the offers page directly at `app.cataliws.com/ws/{your-domain.com}/offers`.

- [Offers](#offers)
  - [Offer Terminology](#offer-terminology)
    - [Offer Variants](#offer-variants)
    - [Offer Addons](#offer-addons)
    - [Offer Subscriptions](#offer-subscriptions)
    - [Offer Reservations](#offer-reservations)
    - [Product Brand, and Version](#product-brand-and-version)
  - [Creating and Managing Offers](#creating-and-managing-offers)
    - [Create a New Offer](#create-a-new-offer)
    - [Manage an Existing Offer](#manage-an-existing-offer)
      - [Delete an Offer](#delete-an-offer)
      - [Add Stock](#add-stock)
      - [Assign an Addon to an Offer](#assign-an-addon-to-an-offer)
      - [Manage an Offer's Details](#manage-an-offers-details)
        - [Reservation Settings](#reservation-settings)
        - [Setup Product Brand](#setup-product-brand)
        - [Offer Variants](#offer-variants-1)
        - [Offer-Related Tasks](#offer-related-tasks)
        - [Offer Photos](#offer-photos)
        - [Other Tools](#other-tools)

## Offer Terminology

Here are some key terms to familiarize yourself with for managing your offers effectively.

### Offer Variants

A variant is a specific version of an offer with distinct properties, such as a different color, size, or price. For example, imagine you sell a "Luxury Silk Men's Shirt" that comes in two styles (Plain, Embroidered) and three colors (Red, Blue, White). Instead of creating six separate offers, you create one main offer and then add variants for each combination:

1.  Default (Style: Plain, Color: White)
2.  Plain - Red (Style: Plain, Color: Red)
3.  Plain - Blue (Style: Plain, Color: Blue)
4.  Embroidered - White (Style: Embroidered, Color: White)
5.  Embroidered - Blue (Style: Embroidered, Color: Blue)
6.  Embroidered - Red (Style: Embroidered, Color: Red)

### Offer Addons
Addons are accessories or extra services sold alongside a main offer. The price of an addon can be included in the main offer's price, or it can have its own price that is added at checkout.

For the shirt example above, addons could be:
- Cufflinks (designed specifically for the shirt)
- Matching Hat

### Offer Subscriptions
This feature applies to services that require recurring payments. It enables automated payment collection from subscribers based on defined terms and prices.

**Note:** This feature may not be enabled for all offer types. If you require it but don't see the option, please contact our support team to request manual activation.

### Offer Reservations
Reservations apply to services that require booking, such as remote or onsite sessions. Examples include:
- Hotel stays
- Consulting sessions
- Event tickets

You will find this option on the offer management page for applicable offer types.

### Product Brand, and Version
These fields allow for extended customization, especially for physical products:
- **Brand**: The manufacturer of the product.
- **Product**: The brand's product name or line.
- **Version/Model**: The specific product model or version.

To set these properties, find the **Product Brand** section on the offer management page and click **Manage**.

## Creating and Managing Offers

Here’s how to get started with creating and publishing offers on your website.

### Create a New Offer
To create a new offer:

1. Navigate to your Offers page: `app.cataliws.com/ws/{your-domain.com}/offers`.
2. Find and click the **Start** button in the bottom-right corner of the page.
3. Click the **Create Offer** button.
4. In the pop-up window, click **Choose Photos** to select images for your offer (you can also do this later).
5. Select the offer **Type** and **Category** from the two dropdown menus.
6. Enter a descriptive **Offer Title**.
7. Write the offer **Description** in the text area. You can use Markdown to format your text. The description must be between `128` and `5,120` characters long.
8. Add search **Keywords** to help customers find your offer. Keywords should be comma-separated, and only letters, numbers, and dashes (`-`) are allowed. The total length must be between `25` and `128` characters.
9. For physical products, provide optional packaging information to help calculate shipping costs: `Length`, `Height` (Min: `10cm`), and `Width` in centimeters (`cm`), and `Weight` in grams (`g`) (Min: `100g`).
10. If you wish to publish the offer immediately, check the **Publish** option. Otherwise, it will be saved as a draft.
11. If you are satisfied with your input, click the **Save** button.

If all goes well, your offer will be saved. You can then refresh the offer list to see the new entry at the top. If you encounter an error, an explanation will appear with instructions on how to resolve it.

### Manage an Existing Offer

On the **Offers Page**, you will see a list of all your created offers. Each entry has quick action buttons to `Manage`, `Delete`, `Create Addon`, and `Add Stock`.

#### Delete an Offer
To permanently delete an offer, click the `Delete` button and confirm the prompt. Since a deleted offer cannot be recovered, consider temporarily unpublishing it from the **Offer Manager** if you might need it later. An offer that has already been purchased cannot be deleted, but you can disable it to remove it from your public website.

#### Add Stock
To quickly add stock to the default variant of an offer, click the **Stock** button on the list item. You can manage stock for individual variants from within the **Offer Manager**.

#### Assign an Addon to an Offer
To assign existing addons to an offer, click the **Addon** button on the list item and select from the available addons.

**To create addons and populate your addon list:**
1. Click the **Start** button on the offers page and then click the **Addons** button.
2. **To manage addon categories:**
    1. Click the **Manage Categories** link.
    2. Click the **Plus (+)** button to add a new category.
    3. Fill in the `Title`, optional `Description`, and a unique `Name`.
    4. Click **Save**.
3. **To create a new addon:**
    1. Click the **Plus (+)** button in the Addons window.
    2. Enter a `Title`, select a `Category`, and set a `Price` (leave blank if it has no extra cost).
    3. Check `Auto Select` if the addon should be automatically added to a customer's order.
    4. Uncheck `Multi Select` if customers can only choose one of this addon type per order.
    5. Click the **Save** button when you're done.

#### Manage an Offer's Details
Click the **Manage** button on any offer in the list to open the **Offer Manager**. From here, you can edit all aspects of the offer.

##### Reservation Settings
To configure booking options, click the **Manage** link in the **Reservation** section. Refer to the [Offer Reservations](#offer-reservations) explanation for more details.

In the **Reservation Settings** window:
1.  Choose the `Service Location` (in-person or virtual).
2.  Choose the `Meeting Service` (e.g., Google Meet, phone call).
3.  The `Show quantity count` option controls whether the number of booked items appears in confirmation emails. Turn this off if you prefer not to display this count.
4.  Enter an optional custom `Confirmation Message` to be included in the confirmation email.
5.  Enter an optional `Post attendance greeting` to be sent to customer.
6.  Click the **Save** button.

##### Setup Product Brand
Click the **Manage** link in the **Product Brand** section. In the window that appears:
1.  Choose a **Brand name** from the dropdown menu, or create a new one.
2.  Choose a **Product** from the dropdown menu, or create a new one.
3.  Choose a **Version**, or create a new one.
4.  Enter the **Release Year**.
5.  Click **Save** when ready.

##### Offer Variants
In the **Order Variants** section of the Offer Manager, you will see a list of variants created for the current offer. The **Extra** button allows you to customize additional options for that offer type, such as available colors or clothing sizes. These options vary depending on the offer type.

To add a **new variant**, click the **Add variant** link and fill out the form:
1. `Title` (3 - 56 characters)
2. `Price` (can be `0.00`)
3. `Stock` quantity
4. `Weight` in grams (Min: `100g`)
5. `Length`, `Height`, and `Width` in centimeters (Min: `10cm`)
6. In the `Peculiar Features` section, enter feature/value pairs (e.g., `Material`/`Cotton`). Click **Add feature** to add more.
7. Click the **Save** button.

##### Offer-Related Tasks
In the **Pending Tasks** section, you may see a list of items that need your attention. Follow the instructions provided to complete them.

##### Offer Photos
In the **Offer Photos** section, you can see all uploaded images for the offer.
- To upload more, click the **Upload** link.
- To manage existing photos, click **Manage Photos**. In the file browser that pops up, click the cog (settings) icon on an image to open the tools menu. Click **Unset** to remove the photo from the offer, or use the other tools to edit the caption, crop, or rotate the image.

##### Other Tools
Explore other tools in the Offer Manager, such as `stock log` and `offer status`. If the offer is currently in `Draft` or `Disabled` mode, a button will appear in the top-right corner allowing you to publish or enable it.

---

[<< Back to main menu](/catali-dashboard/README.md) | [Top](#offers)