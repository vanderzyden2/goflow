<h1 id="goflow-user-guide">goflow User Guide</h1>
<h2 id="table-of-contents">Table of Contents</h2>
<ul>
<li><a href="#Products">Products</a></li>
<li><a href="#Adjustments">Adjustments</a></li>
<li><a href="#Productions">Productions</a></li>
<li><a href="#Moves">Moves</a></li>
</ul>
<h2 id="introduction-to-goflow-products">Introduction to GoFlow Products</h2>
<p>GoFlow is a transaction-based system. Orders come in, purchase orders go out, purchase receipts come in. Product information runs through it all, so entering good product data is vital.</p>
<h3 id="the-importance-of-product-information-in-goflow">The importance of product information in GoFlow</h3>
<p>Correct product information is the foundation. Product data is used throughout GoFlow, everywhere. To have accurate inventory management and listings in your channels, it is essential to ensure that product information is accurate.</p>
<p>A GoFlow product is a foundational description of an item in your inventory. It is important to distinguish a GoFlow product item from the corresponding listings that you may have on a channel such as Amazon. While listings come and go, the GoFlow product information doesn’t change.</p>
<h3 id="all-goflow-transactions-depend-on-accurate-product-information">All GoFlow transactions depend on accurate product information</h3>
<p>All transactions in GoFlow contain some kind of product data. Let’s say you want to run a sales report by brand: you will see product data that contains the item number that corresponds to the brand.</p>
<h3 id="products-are-manually-added-to-goflow---individually-or-by-upload">Products are manually added to GoFlow - individually or by upload</h3>
<p>If you upload or delete listings on your store, this will automatically update listing records in GoFlow. By contrast, products are always updated manually in GoFlow. You manually add a product to GoFlow. While orders and listings process automatically, products are created manually. Products are added in the Inventory module of GoFlow, either on the Product page or through the import feature.</p>
<p>It’s important to realize that listings do not automatically become products. While GoFlow will readily accept all of your listings from Amazon, there must be a product within GoFlow that will correspond to each of those listings.</p>
<p>A product item number is not created automatically. You choose your own item numbers, but they cannot be changed thereafter.</p>
<h3 id="products-are-central-to-inventory-management-workflow">Products are central to inventory management workflow</h3>
<p>The start of the inventory workflow is to enter products.  For customers who process purchasing through GoFlow, the workflow is as follows:</p>
<ol>
<li>Create a product in your GoFlow inventory.</li>
<li>Generate a purchase order that has at least one item number.</li>
<li>Purchase a product from your vendor.</li>
<li>A purchase order transaction is entered into GoFlow.</li>
<li>You receive product into your warehouse.</li>
<li>A purchase receipt transaction is entered into GoFlow.</li>
<li>The product is in stock.</li>
<li>Integrate a channel account (such as Amazon) with your GoFlow account.</li>
<li>Create a listing for the product on one or more channels.</li>
<li>The channel listing(s) will import automatically.</li>
<li>You manually map the listing(s) to a product.</li>
<li>The listing will get real-time inventory quantity from GoFlow (A channel such as Amazon will not permit sales from listings with zero inventory).</li>
</ol>
<p>When an order comes in, it will only have a listing number, which must map to the product. Product in stock is updated in real-time to reflect inventory, map to listing quantities, and adjust to order shipments.</p>
<h3 id="archiving-a-product">Archiving a product</h3>
<p>While you can archive a product, it isn’t possible to delete it. This is necessary to keep a complete product history.</p>
<p>You can only archive a product if it has zero inventory. On the product page of a zero-inventory product, you can change the Status-hover over the Status and click the pencil icon to change the Status from Active to Archive.</p>
<p>The result of archiving a product is that a product will no longer appear in your product list, when creating a manual order, or when creating a purchase order. An archived product is only visible when you choose to look at your archive.</p>
<h3 id="item-numbers-cannot-change">Item numbers cannot change</h3>
<p>Anything except the item number can be changed.</p>
<h3 id="product-types">Product types</h3>
<p>Consider a merchant who sells cameras in packages of various <a href="http://types.In">types.In</a> addition to cameras, you sell other accessories: lens, case for lens, cleaning cloth , washing solution, batteries. With this complexity, it can be challenging to keep inventory with so many variations. Also, you may wonder: How do you deal with some packages that sell well and others that don’t.</p>
<p>There are three types of products:</p>
<p>Standard — standalone single product. Cannot be sold as a kit.<br>
Group — non-physical package of two or more products. Inventory is not kept for the group.<br>
Kit — physical package of a product of two or more products. The process of disassembly breaks a kit into individual products.</p>
<p>A kit of camera accessories is rather inflexible, and may need to be disassembled if the kits don’t sell. The alternative is to is a group, in which the accessories can be easily mixed in different combinations to be sold in groups.</p>
<h3 id="information-that-is-automatically-added-to-a-product">Information that is automatically added to a product</h3>
<p>Inventory numbers will update dynamically with purchasing and sales transactions. Stock status will be dynamically added to products. Many customers do these things manually, but GoFlow does it automatically. Outside actions such as sales and purchase will automatically change inventory numbers.</p>
<h3 id="product-status">Product status</h3>
<p>You can set a product to be inactive, which disables all listings in all channels that list that product. By contrast, inventory status changes automatically. Product information will not be affected by importing listing data / pictures from a channel.</p>
<p><strong>NOTE:</strong> While it is not yet possible to automatically generate listings from GoFlow products, that feature is in development.</p>
<h2 id="a-idproductscreate-a-product-in-goflowa"><a id="Products">Create a Product in GoFlow</a></h2>
<p>There are three types of products:</p>
<ul>
<li>Standard Products</li>
<li>Group Products</li>
<li>Kit Products</li>
</ul>
<h3 id="add-a-standard-product">Add a Standard Product</h3>
<p>Follow these steps to create a new standard product:</p>
<ol>
<li>
<p>In the menu, click <strong>Inventory &gt; Products</strong>.</p>
</li>
<li>
<p>Click the <strong>New Product</strong> button. <br><br>
<img src="https://i.ibb.co/Fk1dmdK/products-1.png%22" alt="New Product"></p>
</li>
<li>
<p>In the popup window, leave the drop-down choice as <strong>Standard Product</strong> and click the <strong>Next</strong> button. <br><br>
<img src="https://i.ibb.co/6m25Y6T/products-2.png" alt="New Product"></p>
</li>
<li>
<p>On the New Product form, enter the product <strong>Name</strong>, which is a mandatory field. Also enter the <strong>Purchase Order Name</strong>, and <strong>Description</strong>.<br><br>
<img src="https://i.ibb.co/Kq35Q98/products-3.png" alt="New Product"></p>
</li>
<li>
<p>Check the <strong>Perishable</strong> box if this product has an expiration date. Keep in mind that some channels require that you send expiration dates for any perishable product.</p>
</li>
<li>
<p>From the drop-downs, choose a <strong>Brand</strong>, <strong>Manufacturer</strong>, <strong>Condition</strong>, <strong>Category</strong>, and <strong>Compliance</strong>.</p>
</li>
<li>
<p>Choose a <strong>Fulfillment Method</strong>.</p>
</li>
<li>
<p>If not applicable, then uncheck the <strong>Is Sellable</strong> or the <strong>Is Purchasable</strong> box.</p>
</li>
<li>
<p>Complete the SKU section, including the <strong>Units of Measure</strong> and <strong>Identifiers</strong> tabs.</p>
</li>
<li>
<p>In the Inventory section, click the <strong>Add Warehouse</strong> button, choose a <strong>Warehouse</strong> and specify the <strong>Location</strong> (aisle and bin). Also, enter the <strong>Reorder Point</strong>, which is the level at which new stock will be ordered.<br>
<img src="https://i.ibb.co/N26z5Gz/products-4.png" alt="New Product"></p>
</li>
<li>
<p>Complete the <strong>Vendors</strong> section. Click <strong>Add Vendor</strong>, and then enter a <strong>Name</strong>, <strong>Vendor Item Number</strong>, <strong>Quantity</strong>, <strong>Cost</strong>, and <strong>Inventory Expiration Date</strong> .  <br><br>
<img src="https://i.ibb.co/12KfzLb/products-5.png" alt="New Product"></p>
</li>
<li>
<p>Complete the <strong>Shipping section</strong>, including the <strong>Customs &amp; More</strong> tab.</p>
</li>
<li>
<p>Click the <strong>Save</strong> button to commit your changes.</p>
</li>
</ol>
<p>The new standard product will appear in the Products listing. You can search for this product using the Search field at the top of the page.</p>
<h3 id="search-for-a-product">Search for a Product</h3>
<p>To search for the product, go to <strong>Inventory &gt; Products</strong>, then enter a term in the Search field.</p>
<p><strong>Filter the list -</strong> To restrict the items in the list, click the <strong>Filters</strong> drop-down in the top left of the page. Choose a <strong>Product Type</strong>, such as <strong>Single Product</strong>. You can also choose a <strong>Warehouse</strong>, enter one or more tags in the <strong>Tagged</strong> field,  and choose whether the product must be <strong>On Hand</strong> and restrict by <strong>Brand</strong>.</p>
<p><img src="https://i.ibb.co/MM5Jzk5/products-7.png" alt="New Product"></p>
<p><strong>Sort:</strong> To sort the results, hover over a column header to display a small arrow. Click the arrow to sort the list in ascending order on that column; click the arrow again to sort the list descending order on that column.</p>
<p><img src="https://i.ibb.co/mTrzVMR/products-8.png" alt="New Product"></p>
<h3 id="update-a-standard-product">Update a Standard Product</h3>
<p>To view a product, click on that product listing.</p>
<p>If this is not the product that you want to edit, click <strong>Products</strong> link at the top of the page to return to the product list.</p>
<p><strong>NOTE:</strong> Click the <strong>Product</strong> link at the top of the page to return to the products list. The benefit is that you will see the list with your search restriction, filtering, and sorting. Actually, It is not possible to use the back button to return to the products list with the browser back button.</p>
<p>Choose a section to edit and click the small pencil icon.</p>
<p><img src="https://i.ibb.co/9sdGPp7/products-6.png" alt=""></p>
<p><strong>Make changes to an existing product:</strong> Hover over a section, such as the General section, and click the small pencil icon. Make your changes in that section, then click the <strong>Save</strong> button to commit your changes. Click <strong>Cancel</strong> to discard all changes and return the product listing to the previous state.</p>
<h3 id="add-a-group-product">Add a Group Product</h3>
<p>Follow these steps to create a new group product:</p>
<ol>
<li>
<p>In the menu, click <strong>Inventory &gt; Products</strong>.</p>
</li>
<li>
<p>Click the <strong>New Product</strong> button. <br><br>
<img src="https://i.ibb.co/Fk1dmdK/products-1.png%22" alt="New Product"></p>
</li>
<li>
<p>In the popup window, choose <strong>Group Product</strong> from the drop-down and click the <strong>Next</strong> button.<br><br>
<img src="https://i.ibb.co/3TB2ChX/products-9.png" alt="New Product"></p>
</li>
<li>
<p>On the New Product form, enter the product <strong>Name</strong>, which is a mandatory field. Also enter the <strong>Purchase Order Name</strong> and <strong>Description</strong>.</p>
</li>
<li>
<p>Check the <strong>Perishable</strong> box if any product within this group has an expiration date. Keep in mind that some channels require that you send expiration dates for any perishable product.</p>
</li>
<li>
<p>From the drop-downs, choose a <strong>Brand</strong>, <strong>Category</strong>, and <strong>Compliance</strong>.</p>
</li>
<li>
<p>Choose a <strong>Fulfillment Method</strong>.</p>
</li>
<li>
<p>Check one or both of the boxes to indicate that this product group <strong>Is Sellable</strong> or <strong>Is Purchasable</strong>.<br><br>
<img src="https://i.ibb.co/Kq35Q98/products-3.png" alt="New Product"></p>
</li>
<li>
<p>Complete the SKU section, and be sure to enter the information for the product group:  <strong>Item Number</strong>, cost and pricing information, and also choose a <strong>Buyer</strong>.</p>
</li>
<li>
<p>Also, enter information for the product group in the including the <strong>Units of Measure</strong> and <strong>Identifiers</strong> tabs.<br><br>
<img src="https://i.ibb.co/Fz5M7qr/products-10.png" alt="Add a group product"></p>
</li>
<li>
<p>In the Products section,  choose the <strong>Item Number</strong> of the first product that you want to add to this product group. Then enter a <strong>Name</strong>, <strong>Qty</strong> (quantity), and optionally edit the <strong>Price</strong>. The <strong>Total</strong> will automatically display a value that is the <strong>Quantity</strong> multiplied by the <strong>Price</strong>.<br><br>
<img src="https://i.ibb.co/zR9XWKz/products-11.png" alt="New Product"></p>
</li>
<li>
<p>Complete the <strong>Shipping section</strong>, including the <strong>Customs &amp; More</strong> tab.</p>
</li>
<li>
<p>Click the <strong>Save</strong> button to commit your changes.</p>
</li>
</ol>
<p>The new group product will appear in the Products listing. You can search for this product using the Search field at the top of the page.</p>
<h3 id="update-a-group-product">Update a Group Product</h3>
<p>Follow the instructions above on how to search for a product. In the <strong>Filters</strong> dropdown at the top of the Products page, choose <strong>Group</strong> from <strong>Product Type</strong>. Enter a search term in the top-right of the page, and then sort on the <strong>Item Number</strong> column (if necessary).</p>
<p><img src="https://i.ibb.co/kx7yD50/products-14.png" alt="New Product"></p>
<p>In the product list, click the listing of the group product that you want to edit, and the detail page will appear.</p>
<p>If this is not the product that you want to edit, click <strong>Products</strong> link at the top of the page to return to the product list.</p>
<p><strong>NOTE:</strong> Click the <strong>Product</strong> link at the top of the page to return to the products list. The benefit is that you will see the list with your search restriction, filtering, and sorting. Actually, It is not possible to use the back button to return to the products list with the browser back button.</p>
<h3 id="add-a-kit-product">Add a Kit Product</h3>
<p>Follow these steps to create a new kit product:</p>
<ol>
<li>
<p>In the menu, click <strong>Inventory &gt; Products</strong>.</p>
</li>
<li>
<p>Click the <strong>New Product</strong> button.<br><br>
<img src="https://i.ibb.co/Fk1dmdK/products-1.png%22" alt="New Product"></p>
</li>
<li>
<p>In the popup window, choose <strong>Kit Product</strong> from the drop-down and click the <strong>Next</strong> button.<br><br>
<img src="https://i.ibb.co/ZXqfXVx/products-12.png" alt="New Product"></p>
</li>
<li>
<p>On the New Product form, enter the product <strong>Name</strong>, which is a mandatory field. Also enter the <strong>Purchase Order Name</strong> and <strong>Description</strong>.</p>
</li>
<li>
<p>Check the <strong>Perishable</strong> box if any product within this group has an expiration date. Keep in mind that some channels require that you send expiration dates for any perishable product.</p>
</li>
<li>
<p>From the drop-downs, choose a <strong>Brand</strong>, <strong>Manufacturer</strong>, <strong>Condition</strong>, <strong>Category</strong>, and <strong>Compliance</strong>.</p>
</li>
<li>
<p>Choose a <strong>Fulfillment Method</strong>.</p>
</li>
<li>
<p>Check one or both of the boxes to indicate that this product group <strong>Is Sellable</strong> or <strong>Is Purchasable</strong>.<br><br>
<img src="https://i.ibb.co/Kq35Q98/products-3.png" alt="New Product"></p>
</li>
<li>
<p>Complete the SKU section, and be sure to enter the information for the product group: <strong>Item Number</strong>, cost and pricing information, and also choose a <strong>Buyer</strong>.</p>
</li>
<li>
<p>Also, enter information for the product group in the including the <strong>Units of Measure</strong> and <strong>Identifiers</strong> tabs.<br><br>
<img src="https://i.ibb.co/Fz5M7qr/products-10.png" alt="Add a group product"></p>
</li>
<li>
<p>In the Products section,  choose the <strong>Item Number</strong> of the first product that you want to add to this product group. Then enter a <strong>Name</strong>, <strong>Qty</strong> (quantity), and optionally edit the <strong>Price</strong>. The <strong>Total</strong> will automatically display a value that is the <strong>Quantity</strong> multiplied by the <strong>Price</strong>.<br><br>
<img src="https://i.ibb.co/zR9XWKz/products-11.png" alt="New Product"></p>
</li>
<li>
<p>. Complete the <strong>Vendors</strong> section. Click <strong>Add Vendor</strong>, and then enter a <strong>Name</strong>, <strong>Vendor Item Number</strong>, <strong>Quantity</strong>, <strong>Cost</strong>, and <strong>Inventory Expiration Date</strong> .<br><br>
<img src="https://i.ibb.co/12KfzLb/products-5.png" alt="New Product"></p>
</li>
<li>
<p>Complete the <strong>Shipping section</strong>, including the <strong>Customs &amp; More</strong> tab.</p>
</li>
<li>
<p>Click the <strong>Save</strong> button to commit your changes.</p>
</li>
</ol>
<p>The new kit product will appear in the Products listing. You can search for this product using the Search field at the top of the page.</p>
<h3 id="update-a-kit-product">Update a Kit Product</h3>
<p>Follow the instructions above on how to search for a product. In the <strong>Filters</strong> dropdown at the top of the Products page, choose <strong>Kit</strong> from <strong>Product Type</strong>. Enter a search term in the top-right of the page, and then sort on the <strong>Item Number</strong> column (if necessary).</p>
<p><img src="https://i.ibb.co/vP1THFx/products-13.png" alt="New Product"></p>
<p>In the product list, click the listing of the kit product that you want to edit, and the detail page will appear.</p>
<p>If this is not the product that you want to edit, click <strong>Products</strong> link at the top of the page to return to the product list.</p>
<h2 id="a-idadjustmentsadjustmentsa"><a id="Adjustments">Adjustments</a></h2>
<h2 id="a-idproductionsproductionsa"><a id="Productions">Productions</a></h2>
<h2 id="a-idmovesmovesa"><a id="Moves">Moves</a></h2>

